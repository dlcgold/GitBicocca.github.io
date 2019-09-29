# GitBicocca.github.io

## A che serve questa repo?
[GitMib](https://gitbicocca.github.io/index.html) è un'interfaccia per trovare comodamente gli appunti che cerchi! 

Da un anno a questa parte, alcuni studenti del corso di informatica di UNIMIB condividono i propri appunti su GitHub perché credono che l'open source non sia solo una licenza, ma uno stile di vita.

## Come contribuire
Fai una pull request.
Aggiungi il link della tua repo (nb. gli appunti devono essere già completi). 

Supponiamo che tu voglia aggiungere degli appunti di Linguaggi e Computabilità. Cerca la parte di codice formattata in questo modo:

```html
<div class="tab-pane fade" id="list-LC" role="tabpanel" aria-labelledby="list-LC-list">
  <a href="https://github.com/JacopoDeAngelis/Appunti-universitari/tree/master/Linguaggi%20e%20computabilit%C3%A0">LC - Jacopo</a> <br>
  <a href="https://github.com/bigboss98/appunti/tree/master/Computabilit%C3%A0">LC - bigboss98</a>
```

Vai a capo con `<br>` e scrivi:
```html
<a href="tuo-link">LC - tuo-nome</a>
```

Ricorda poi di incrementare il valore del badge associato:
```html
<a class="list-group-item list-group-item-action" id="list-LC-list" data-toggle="list" href="#list-LC" role="tab" aria-controls="LC">
  <span class="badge badge-success badge-pill">2</span> Linguaggi e computabilità </a>
```
diventerà
```html
<a class="list-group-item list-group-item-action" id="list-LC-list" data-toggle="list" href="#list-LC" role="tab" aria-controls="LC">
  <span class="badge badge-success badge-pill">3</span> Linguaggi e computabilità </a>
```
