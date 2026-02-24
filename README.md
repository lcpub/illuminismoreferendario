# Al lume della Ragione – Enlightenment Voting Simulator

An interactive web page that lets you explore how Enlightenment thinkers might vote on a modern referendum. You assign importance scores (1–10) to six political-justice criteria, and the system calculates whether your preferences align more with a "YES" or "NO" outcome. You can compare your profile with those of nine historical philosophers (Montesquieu, Beccaria, Madison, Hume, Burke, Kant, Tocqueville, Diderot, Filangieri), view radar charts, and read imaginary "Persian letters" written in their style.

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

---

## Features

- **Voting interface** – assign a value (1–10) to each of six criteria:
  1. Distance of judging from political passions  
  2. Perceived impartiality of the judge  
  3. Liberty as security (trust in the process)  
  4. Clarity of laws and limited interpretation  
  5. Safeguards against capture and credible discipline  
  6. Long‑term checks and balances  
- **Real‑time normalisation** – your votes are converted into weights that sum to 1.  
- **YES / NO indices** – computed as weighted averages of pre‑assigned scores for each criterion (based on a cautious Enlightenment‑style interpretation).  
- **Radar chart** – visually compares your priorities with those of any selected philosopher.  
- **Philosopher profiles** – nine historical figures with authentic quotations from their works, biographical notes, and their own vote patterns.  
- **"Persian letters"** – each profile (and the user) receives a stylised letter summarising their stance in 18th‑century epistolary form.  
- **Compare mode** – overlay a philosopher’s votes on the radar chart without changing your own scores.  
- **Detailed contributions** – expandable tables show how each criterion contributes to the final YES‑NO difference.  
- **Notes & bibliography** – a collapsible section explains the model’s “prudential tilt” and lists both original sources and contemporary academic references (economics/political science).  
- **Visitor counter** – simple localStorage‑based counter.  
- **Fully responsive** – works on smartphones, tablets and desktops; radar labels adapt to screen size.

---

## Technologies used

- HTML5  
- CSS3 (custom properties, flexbox, grid)  
- Vanilla JavaScript (no external libraries)  
- Canvas API for the radar chart

---

## How to use

1. Open `index.html` in any modern browser.  
2. Adjust the six sliders (or type numbers) according to how important you think each criterion is.  
3. Watch the YES/NO indices, the winner badge and the radar chart update instantly.  
4. Click **“Confronta questi voti con i miei”** on any philosopher card to overlay their profile on the radar.  
5. Click **“Giudizio del profilo”** to see a detailed evaluation and a personalised “Persian letter” for that philosopher.  
6. Expand the **“Note e bibliografia”** section at the bottom for background information and full references.

---

## File structure

```
├── index.html               # main page (rename this file to index.html)
├── img/                      # local portrait images (optional)
│   ├── montesquieu.png
│   ├── beccaria.jpg
│   ├── madison.jpg
│   └── ... (all nine portraits)
└── README.md                 # this file
```

If local images are missing, the script automatically falls back to Wikimedia Commons URLs.

---

## Credits

- **Project curator:** Luca Cetara Publishing (1796 & 2026)  
- **Idea and development:** inspired by the political thought of the Enlightenment and by contemporary research on weighted voting, judicial independence and democratic representation.  
- **Historical quotations:** taken from the authors’ original works (public domain).  
- **Contemporary sources:** Shapiro, Hirschl, Ceccarini, Di Lonardo & Dragu, Dal Bó et al., and articles in *Social Choice and Welfare* / *European Economic Review*.

---

## License

This work is licensed under a [Creative Commons Attribution‑ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).  
You are free to share and adapt it, provided you give appropriate credit and distribute your contributions under the same license.

---

---

# Al lume della Ragione – Simulatore di voto illuminista

Una pagina web interattiva che permette di esplorare come gli illuministi potrebbero votare in un moderno referendum. L’utente assegna punteggi di importanza (1–10) a sei criteri politico‑giudiziari, e il sistema calcola se le sue preferenze si avvicinano di più a un esito “SÌ” o “NO”. È possibile confrontare il proprio profilo con quello di nove filosofi storici (Montesquieu, Beccaria, Madison, Hume, Burke, Kant, Tocqueville, Diderot, Filangieri), visualizzare grafici radar e leggere immaginarie “Lettere persiane” scritte nel loro stile.

[![Licenza: CC BY-SA 4.0](https://img.shields.io/badge/Licenza-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/deed.it)

---

## Caratteristiche

- **Interfaccia di voto** – assegna un valore (1–10) a ciascuno dei sei criteri:
  1. Distanza del giudicare dalle passioni politiche  
  2. Terzietà e imparzialità percepita del giudice  
  3. Libertà come sicurezza (fiducia nel processo)  
  4. Chiarezza delle leggi e limitazione dell’interpretazione  
  5. Preservativi contro la cattura e disciplina credibile  
  6. Contrappesi nel lungo periodo  
- **Normalizzazione in tempo reale** – i voti vengono convertiti in pesi che sommano a 1.  
- **Indici SÌ / NO** – calcolati come medie ponderate di punteggi pre‑assegnati per ogni criterio (basati su un’interpretazione prudenziale di stampo illuminista).  
- **Grafico radar (prospetto radiale)** – confronta visivamente le tue priorità con quelle di un filosofo selezionato.  
- **Profili dei filosofi** – nove figure storiche con citazioni autentiche dalle loro opere, note biografiche e i loro stessi schemi di voto.  
- **“Lettere persiane”** – ogni profilo (e l’utente) riceve una lettera stilizzata che riassume la sua posizione in forma epistolare settecentesca.  
- **Modalità confronto** – sovrapponi i voti di un filosofo sul radar senza modificare i tuoi punteggi.  
- **Contributi dettagliati** – tabelle espandibili mostrano come ogni criterio incida sulla differenza finale SÌ‑NO.  
- **Note e bibliografia** – una sezione a scomparsa spiega il “tilt prudenziale” del modello e elenca sia le fonti originali che i riferimenti accademici contemporanei (economia / scienza politica).  
- **Contatore visite** – semplice contatore basato su localStorage.  
- **Completamente responsive** – funziona su smartphone, tablet e desktop; le etichette del radar si adattano alla dimensione dello schermo.

---

## Tecnologie utilizzate

- HTML5  
- CSS3 (variabili personalizzate, flexbox, grid)  
- JavaScript puro (nessuna libreria esterna)  
- Canvas API per il grafico radar

---

## Come usare

1. Apri `index.html` in un browser moderno.  
2. Regola i sei cursori (o digita i numeri) in base all’importanza che attribuisci a ogni criterio.  
3. Osserva gli indici SÌ/NO, il badge del vincitore e il radar aggiornarsi istantaneamente.  
4. Clicca **“Confronta questi voti con i miei”** su qualsiasi scheda filosofo per sovrapporre il suo profilo sul radar.  
5. Clicca **“Giudizio del profilo”** per vedere una valutazione dettagliata e una “Lettera persiana” personalizzata per quel filosofo.  
6. Espandi la sezione **“Note e bibliografia”** in fondo alla pagina per informazioni di contesto e riferimenti completi.

---

## Struttura dei file

```
├── index.html               # pagina principale (rinominare in index.html)
├── img/                      # immagini locali dei ritratti (opzionale)
│   ├── montesquieu.png
│   ├── beccaria.jpg
│   ├── madison.jpg
│   └── ... (tutti e nove i ritratti)
└── README.md                 # questo file
```

Se le immagini locali sono assenti, lo script utilizza automaticamente gli URL di Wikimedia Commons come fallback.

---

## Crediti

- **Curatela del progetto:** Luca Cetara Publishing (1796 & 2026)  
- **Idea e sviluppo:** ispirato al pensiero politico dell’Illuminismo e alla ricerca contemporanea su voto ponderato, indipendenza giudiziaria e rappresentanza democratica.  
- **Citazioni storiche:** tratte dalle opere originali degli autori (pubblico dominio).  
- **Fonti contemporanee:** Shapiro, Hirschl, Ceccarini, Di Lonardo & Dragu, Dal Bó et al., e articoli su *Social Choice and Welfare* / *European Economic Review*.

---

## Licenza

Quest’opera è distribuita con licenza [Creative Commons Attribuzione‑Condividi allo stesso modo 4.0 Internazionale](https://creativecommons.org/licenses/by-sa/4.0/deed.it).  
Sei libero di condividere e modificare il materiale, a patto di attribuire la paternità adeguata e distribuire i contributi con la stessa licenza.
