# web\_pilates
Template web site in xhtml5 per Marta

## Configurazione

### Far funzionare le pagine anche su harddisk, cdrom e memoria usb o altro

Per farlo funzionare senza server web si deve accettare che i percorsi finiscano con `index.html`, altrimenti commentare nel file `_config.yml` la riga

    # index: "index.html"

### Per disabilitare gli eventi

Commentare tutte le rige

    # events
    collections:
      events:
        output: true

eliminare l'elemento ["eventi", "/events/"] dalla riga sotto
    
    # site Menu [ [ neme_link, absolute_path ], ... ]

### Togliere il blog

eliminare l'elemento ["blog", "/blog/"] dalla riga sotto

    # site Menu [ [ neme_link, absolute_path ], ... ]

Ed eliminare le directory `/blog` e `/_post`

### Togliere il log

Il log stampa, in ordine cronologico, ogni cosa stampata altrove, siano
post, eventi ecc.

eliminare l'elemento ["log", "/log/"] dalla riga sotto

    # site Menu [ [ neme_link, absolute_path ], ... ]

Ed eliminare le directory `/log`

### Messaggi sulla Home

I messagi in home si trovano in `_home`. I messaggi sono ordinati 
secondo
il nome dei file.

