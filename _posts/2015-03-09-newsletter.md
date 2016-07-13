---
title: "Struttura dei documenti e Matematica in undercustodian.github.io"
author: UnderCustodian
user: undercustodian
layout: post
---

Verifichiamo la struttura delle sezioni

Bla bla

# Sezione

Boa bla

## Sottosezione

Bla Bla

### Sotto-Sottosezione

Bla bla

#### Titolo 4 (Teorema)

Bla bla

##### Titolo 5 (paragrafo)

Bla bla

###### Titolo 6 (Sotto-paragrafo)

Bla Bla

#### Note 1:
Per quanto riguarda i capitoli non esistono negli articoli, ma un articolo può essere considerato un capitolo di un libro, che ha nome capitolo il titolo dell'articolo. Un libro è una lista di links a degli articoli, che verranno chiamati capitoli del libro. Un libro può anche essere una lista di links di altri libri, che verranno chiamati parti del libro. Concludendo scriviamo articoli e li mettiamo come capitoli di un libro, che serve solo per ordinare e organizzare. Può capitare che un capitolo sia presente in più libri. Parti di articoli non possono essere presenti in altri articoli. Gli articoli possono contenere i links ad altri articoli o libri. L'articolo deve contenere una parte di ripasso dei concetti usati e i links ad articoli che trattano questi concetti; tali articoli potrebbero essere i capitoli precedenti, se si sta leggendo un libro.

#### Nota 2:
Importante è scrivere le formule in modo intuitivo usando carattere ascii, questo lo otteniamo con [AsciiMath](http://asciimath.org/) che abbiamo già implementato, visto che è implementato da  [MathJax](http://mathjax.org/), già implementato in precedenza; basta riconfigurarlo in modo appropriato.

Per le formule usiamo ascii:

    \`1/2 + 3/4 = 5/4\` \`[[a, b],[c, d]]\`

mettendo le formule fra due apici inversi, protetti da una barra inversa, visto che markdown interpreta il contenuto tra apici inversi come codice da presentare tale quale;

si ottiene \`1/2 + 3/4 = 5/4\` \`[[a, b],[c, d]]\`

che è quello che ci aspettiamo; inoltre possiamo introdurre anche formule in LaTeX mettendole tra dollaro `$\frac{1}{2}$` da $\frac{1}{2}$ grazie a [MathJax](http://mathjax.org/).

Ho riscontrato non pochi problemi nell'utilizzo  dell'apice inverso, visto che viene usato da markdown.

Ora cerco di incasinarmi scrivendo

    \`sum_(i=1)^n i = (n(n+1))/2\`

e anche

    \`x * y\`

che mi danno rispettivamente

\`sum_(i=1)^n i = (n(n+1))/2\`

e

\`x * y\`


Le formule si riescono a scrivere basta proteggere l'apice inverso con un barra inversa. Potrei usare LaTeX per scrivere l'apice inverso

    $\`$ ma $\`$

da

$\`$ ma $\`$

però crea un po di problemi, meglio evitare di usare il simbolo di l`apice inverso.  
proviamo ad usare questo codice

    \&#96;

da

\&#96;

non prolunghiamoci oltre ...

#### Nota 3: Cosa si vuole
Scrivere appunti di getto, quindi in modo intuitivo, senza addentrarsi troppo nella formattazione, che abbiano una bella presentazione. Scrivi, cancelli, riscrivi, modificare ecc. Per avvicinarsi a questo manca un modo semplice per disegnare, ottenibile anche affiancando un programma di grafica o aiutandosi con carta e penna. La grafica sarà un altro argomento da affrontare, per ora diamoci dentro di xfig e inkscape e svg e POV-Ray, carta e matita.


[sorgente](https://github.com/undercustodian/undercustodian.github.io/blob/master/blog/_posts/2015-03-09-newsletter.md)

[firma: Undercustodian](http://undercustodian.github.io/sig/2015-03-09-newsletter.md.sig)


