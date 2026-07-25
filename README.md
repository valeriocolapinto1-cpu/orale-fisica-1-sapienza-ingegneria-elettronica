# Fisica 1 — Orale Trainer

App web per preparare l'**esame orale di Fisica 1** (Ingegneria Elettronica, Sapienza) in 6 giorni — esame il **27 luglio**.

**👉 Aprila qui: [valeriocolapinto1-cpu.github.io/orale-fisica-1-sapienza-ingegneria-elettronica](https://valeriocolapinto1-cpu.github.io/orale-fisica-1-sapienza-ingegneria-elettronica/)**

Tutto in un unico `index.html`: nessun build, nessun backend, nessun account. Funziona con doppio clic, da GitHub Pages e da Safari su iPhone; i dati restano nel `localStorage` del browser.

## Cosa contiene

- **33 argomenti completi** divisi in 4 aree (cinematica e oscillazioni, lavoro ed energia, sistemi di punti e corpo rigido, fluidi e termodinamica): ogni scheda si apre con **«L'idea in sintesi»** (l'intuizione fisica in evidenza) e prosegue con definizioni, **derivazioni passo-passo** con formule (MathJax), ipotesi di validità, casi limite, errori tipici, checklist per l'orale e domande di approfondimento.
- **Simulazioni interattive** (canvas) per costruire l'intuizione: moto armonico, oscillatore smorzato (i tre regimi), risonanza, pendolo semplice (dove l'approssimazione dei piccoli angoli cede), gara dei momenti d'inerzia sul piano inclinato, campo delle velocità nel rotolamento, ciclo di Carnot nel piano p-V e urti. Slider sui parametri fisici e valori aggiornati in tempo reale.
- **Simulazione d'orale** con **modalità facile / difficile**: estrazione casuale pesata verso gli argomenti deboli, timer ed esposizione a voce. In *difficile* esponi a memoria come all'esame (con la checklist rivelabile se ti blocchi); in *facile* segui la **checklist a schermo** e spunti i punti man mano. Alla fine, autovalutazione 0–3 sulla checklist e domande di approfondimento.
- **Quiz di allenamento**: costruisci un quiz su misura scegliendo aree, tipo di domande e numero. Le domande sono generate dai contenuti: *formula → argomento*, *argomento → formula*, *riconosci l'errore* (scelta multipla con feedback immediato) e *flashcard a voce* (autovalutate). A fine quiz: punteggio, dettaglio per area e possibilità di segnare come «da ripassare» gli argomenti sbagliati.
- **Piano di studio automatico** fino all'esame: distribuisce gli argomenti sui giorni rimanenti (peso doppio su corpo rigido e termodinamica), riserva gli ultimi 2 giorni a solo ripasso e ridistribuisce ciò che non completi.
- **Ripasso spaziato (SM-2 semplificato)**: ogni argomento ha uno stato (mai visto → debole → consolidato → padroneggiato) e una data di prossimo ripasso; la dashboard mostra la preparazione complessiva e la copertura per area con anelli animati.
- **Formulario stampabile** generato dalle formule chiave, raggruppato per area.

Interfaccia in **tema scuro moderno**: superfici in vetro (glassmorphism) con bordi sottili, sfondo aurora animato, accenti a gradiente indigo-violetto e micro-animazioni ovunque (comparse a cascata, anelli e barre che si riempiono, transizioni fluide, feedback dei quiz). Navigazione a tab in basso su mobile e sidebar su desktop, schede a schermo intero. Rispetta `prefers-reduced-motion`.

## Uso

Nessuna installazione: apri `index.html` nel browser (o il link GitHub Pages qui sopra). Serve la connessione solo al primo caricamento per il rendering delle formule (CDN MathJax).
