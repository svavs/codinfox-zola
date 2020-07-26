+++
title = "Example content"
template = "post.html"

[taxonomies]
tags = ["example"]
categorie = ["writing post", "docs"]
+++


<div class="message">
  Ciao! Questo è un esempio di blog post che mostra alcune tipoligie di contenuto HTML supportate da questo tema.
</div>

Cum sociis natoque penatibus et magnis <a href="#">dis parturient montes</a>, nascetur ridiculus mus. *Aenean eu leo quam.* Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere consectetur est at lobortis. Cras mattis consectetur purus sit amet fermentum.

> Curabitur blandit tempus porttitor. Nullam quis risus eget urna mollis ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.

Etiam porta **sem malesuada magna** mollis euismod. Cras mattis consectetur purus sit amet fermentum. Aenean lacinia bibendum nulla sed consectetur.

<!-- more -->

## Elementi HTML incorporati

HTML definisce una lunga lista di tag incorporati a disposizione, una lista completa dei quali è possibile trovare nel [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

- **Per il testo in grassetto**, usare  `<strong>`.
- *Per il testo in corsivo*, use `<em>`.
- Abbreviazioni, come <abbr title="HyperText Markup Langage">HTML</abbr> dovrebbero essere `<abbr>`, con un attributo `title` opzionale per la frase completa.
- Citazioni, come <cite>&mdash; Mark otto</cite>, dovrebbero far uso di `<cite>`.
- Il testo <del>barrato</del> dovrebbe usare `<del>` e il testo <ins>sottolineato</ins> dovrebbe essere inserito con `<ins>`.
- Il <sup>testo</sup> in apice utilizza `<sup>`, mentre quello in <sub>pedice</sub> utilizza `<sub>`.

La maggior parte di questi elementi hanno uno stile impostato dai browser con alcune modifiche di questo tema.

## Intestazione

Vivamus sagittis lacus vel augue rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.

### Codice

Cum sociis natoque penatibus et magnis dis `codice sorgente` montes, nascetur ridiculus mus.

```js
    // Esempio che può essere avviato direttamente nella console JavaScript

    // Crea una funzione che prende due argomenti e ritorna la loro somma
    var adder = new Function("a", "b", "return a + b");

    // Chiamata alla funzione
    adder(2, 6);
    // > 8
```

Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa.

### Elenchi

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.

* Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
* Donec id elit non mi porta gravida at eget metus.
* Nulla vitae elit libero, a pharetra augue.

Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae elit libero, a pharetra augue.

1. Vestibulum id ligula porta felis euismod semper.
2. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
3. Maecenas sed diam eget risus varius blandit sit amet non magna.

Cras mattis consectetur purus sit amet fermentum. Sed posuere consectetur est at lobortis.

<dl>
  <dt>HyperText Markup Language (HTML)</dt>
  <dd>Il linguaggio usato per descrivere e definire il contenuto di una pagina Web</dd>

  <dt>Cascading Style Sheets (CSS)</dt>
  <dd>Utilizzato per definire l'aspetto del contenuto Web</dd>

  <dt>JavaScript (JS)</dt>
  <dd>Il linguaggio di programmazione usato per realizzare siti Web avanzati e applicazioni</dd>
</dl>

Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.

### Tabelle

Aenean lacinia bibendum nulla sed consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

<table>
  <thead>
    <tr>
      <th>Nome</th>
      <th>Voti positivi</th>
      <th>Voti negativi</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td>Totale</td>
      <td>21</td>
      <td>23</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>10</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Charlie</td>
      <td>7</td>
      <td>9</td>
    </tr>
  </tbody>
</table>

Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.

### Matematica

Test per le equazioni matematiche:

$$ J_\alpha(x) = \sum\limits_{m=0}^\infty \frac{(-1)^m}{m! \, \Gamma(m + \alpha + 1)}{\bigl({\frac{x}{2}}\bigr)}^{2 m + \alpha} $$

-----

Servono altri esempi in questa pagina? <a href="https://github.com/poole/poole/issues/new">Apri una issue.</a>
