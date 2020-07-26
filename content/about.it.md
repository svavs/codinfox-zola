+++
template = "page.html"
title = "Cos'è questo sito"
+++

<p class="message">
  Ciao! Questo è un esempio di pagina. Sentiti libero di personalizzarla come più ti piace dopo averla scaricata. Iniziamo!
</p>

Questo è un tema per [Zola](https://www.getzola.com) ispirato a [Codinfox-Lanyon](https://codinfox.github.com/), un tema basato su Lanyon e realizzato per [Jekyll](http://jekyllrb.com).
È possibile vedere una dimostrazione [qui](https://codinfox-zola.vercel.app/).

Questo è un tema che pone attenzione al contenuto prima di tutto, riponendo la navigazione in un tiretto laterale nascosto.

* Sviluppato per [Zola](https://www.getzola.com)
* Distribuito su Github e ospitato gratuitamente su [Github Pages](https://pages.github.com) e [Vercel](https://vercel.com)
* Codice scritto con [Spacemacs](https://www.spacemacs.org)

Questo tema supporta:

1. Diverse colorazioni: è possibile scegliere il colore preferito per il tema (cambiandolo nel `_config.scss`)
2. La possibilità di cambiare posizione alla barra laterale (è possibile invertirla modificando la variabile booleana presente in `_config.scss`)
3. L'integrazione di FontAwesome, MathJax, Disqus e Google Analytics
4. Supporto per i siti multilingue
5. Numerosi miglioramenti rispetto all'originale Lanyon e Codinfox-Lanyon

Tutte le variabili di configurazione e il loro significato sono all'interno dei rispettivi file di configurazione:

- `config.toml` (per le variabili di configurazione di Zola ed alcune valiabili extra richieste da questo tema),
- `author.toml` (per le informazioni personali da visualizzare riguardo l'autore del sito),
- `nav.toml` (per la definizione delle voci del menu di navigazione disponibile nella barra laterale del sito)
- `_config.scss` (per la definizione di alcune personalizzazioni nello stile css).

Le opzioni sono semplici e descritte nei commenti.

Visita il repository [Github](https://github.com/svavs/codinfox-zola) per maggiori informazioni e per contribuire.

Hai suggerimenti o domande? Allora [apri una issue su Github](https://github.com/svavs/codinfox-zola/issues/new) o [chiedimi su Twitter](https://twitter.com/svavs).

### Installazione e utilizzo

Per usare questo tema è sufficiente seguire le istruzioni richieste per l'installazione di un qualsiasi tema realizzato per Zola.

Semplicemente clonare questo repository nella cartella `themes` del sito.

Fatto ciò, definire le extra variabili nel `config.toml` (è possibile trovarle nel `config.toml` del tema stesso), creare e definire i file di configurazione `author.toml` e `nav.toml` nella cartella principale del sito (lo stesso livello del `config.toml`), ed ecco fatto!

Per definire una immagine personalizzata per la home page, basta salvare un file immagine nella sottocartella `static/img/` ed impostare il percorso nella variabile config.extra.image.

Adesso è possibile creare le pagine del sito salvando i file in formato Markdown nella cartella `content` del sito stesso come si fa per qualsiasi sito realizzato con Zola.

Se si vuole gestire un Blog con questo tema, è sufficiente creare una sotto-cartella di `content` contenente tutti i post del blog scritti in formato Markdown. Zola genera automaticamente una sezione per questa nuova cartella. È possibile vedere un esempio nella [live demo](https://codinfox-zola.vercel.app/blog/).

## Licenza

Rilasciato sotto licenza open source [MIT license](LICENSE.md).


# TODO
 - recaptcha per nascondere l'indirizzo email (https://developers.google.com/recaptcha/intro)
 - collegamenti multilingue della topbar nascosti per le pagine principali di sezioni
