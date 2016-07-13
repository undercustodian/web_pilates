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


