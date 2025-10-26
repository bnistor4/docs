# Struttura Pagine — FSEng

Questa è la “mappa” del nuovo sito. Ogni file descrive una pagina: cosa vogliamo dire, in che ordine, quali elementi inserire (testi, immagini, call to action). L’obiettivo è che anche chi non lavora ogni giorno nel digitale possa capire con facilità come sarà organizzato il sito.

Dentro ogni documento troverai indicazioni su:
- **Il senso della pagina** (perché esiste e cosa deve chiarire).
- **Le sezioni principali** (hero, blocchi di contenuto, esempi, FAQ).
- **Le azioni suggerite** per il visitatore (es. “Richiedi consulenza”, “Parla con noi”).
- **Eventuali materiali utili** (immagini, grafici, dati) da raccogliere.

## Mappa dei file

```
pages/
├── home.md                     # Panoramica iniziale con servizi, CTA e prove
├── chi-siamo.md                # Storia, valori e team
├── contatti.md                 # Form, recapiti, calendario
├── blog.md                     # Linee editoriali e struttura archivio articoli
├── progetti.md                 # Archivio case study e filtri
├── progetti-template.md        # Campi ACF e layout per singolo case study
├── soluzioni/
│   ├── overview.md             # Introduzione alle 5 macro-categorie
│   ├── _template.md            # Schema da duplicare per nuovi cluster
│   ├── ingegneria-antincendio/
│   │   ├── overview.md         # Pillar rosso: approccio FSE/PBD
│   │   ├── dinamica-incendio-compartimento.md
│   │   ├── evacuazione-comportamento-umano.md
│   │   ├── controllo-fumi-aset-rset.md
│   │   ├── valutazione-rischio-resilienza.md
│   │   ├── soluzioni-alternative-codice.md
│   │   └── nuove-tecnologie.md
│   ├── impianti-antincendio/
│   │   ├── overview.md         # Pillar blu: progettazione impianti
│   │   ├── sistemi-rilevazione-allarme.md
│   │   ├── sistemi-sprinkler-idranti.md
│   │   ├── enfc-senfc-svof.md
│   │   ├── sistemi-speciali.md
│   │   └── supervisione-manutenzione.md
│   ├── resistenza-al-fuoco/
│   │   ├── overview.md         # Pillar giallo: ingegneria strutturale
│   │   ├── materiali-proprieta.md
│   │   ├── curve-naturali-collasso.md
│   │   └── modellazioni-accoppiate.md
│   ├── ingegneria-forense/
│   │   ├── overview.md         # Pillar grigio: indagini post-evento
│   │   └── analisi-post-evento.md
│   └── sostenibilita-antincendio/
│       ├── overview.md         # Pillar verde: energy transition e resilienza
│       └── energy-transition.md
├── settori/
│   ├── overview.md             # Come lavoriamo per i diversi ambiti
│   ├── industria-logistica.md
│   ├── terziario-retail.md
│   ├── sanita-istruzione.md
│   ├── infrastrutture-mobilita.md
│   ├── cultura-heritage.md
│   ├── energia-nuove-tecnologie.md
│   └── eventi-crowd-management.md
└── risorse/
    ├── overview.md             # Hub contenuti utili
    ├── calcolatrici.md         # Strumenti tecnici disponibili
    ├── normativa.md            # Raccolta codici e linee guida
    └── faq.md                  # Domande frequenti organizzate per tema
```

## Come orientarsi
- Se vuoi solo **capire l’architettura**, inizia da `soluzioni/overview.md`, `settori/overview.md` e `risorse/overview.md`: raccontano le cinque aree principali, i settori serviti e gli spazi informativi.
- Se devi **leggere una pagina specifica**, apri il file corrispondente: una pagina = un file.
- Se qualcosa non è chiaro o manca un contenuto, aggiungi un commento nel file o segnala in `plan/work-plan.md`.
- Le call to action sono già suggerite: è sufficiente verificarle insieme quando passeremo alla fase di design.

## Note operative
- I file sono in formato testo (Markdown) così è facile leggerli, modificarli e tenere traccia delle versioni.
- Se serve aggiungere una nuova pagina, basta duplicare `_template.md`, compilarlo e avvisare così aggiorniamo la sitemap (`ia/sitemap.md`).
- Le pagine nella root (`home.md`, `chi-siamo.md`, ecc.) sono le sezioni principali; le sottocartelle raccolgono le aree tematiche.
- Solo questa cartella è condivisa via GitHub: ogni aggiornamento resta tracciato e si può commentare facilmente.
- Per una visione d’insieme del progetto (tempistiche, priorità) consulta `plan/work-plan.md`.
