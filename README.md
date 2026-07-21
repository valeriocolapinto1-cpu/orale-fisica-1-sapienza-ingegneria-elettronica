# Fisica 1 — Orale Trainer

App web per preparare l'**esame orale di Fisica 1** (Ingegneria Elettronica, Sapienza) in 6 giorni — esame il **27 luglio**.

**👉 Aprila qui: [valeriocolapinto1-cpu.github.io/orale-fisica-1-sapienza-ingegneria-elettronica](https://valeriocolapinto1-cpu.github.io/orale-fisica-1-sapienza-ingegneria-elettronica/)**

Tutto in un unico `index.html`: nessun build, nessun backend, nessun account. Funziona con doppio clic, da GitHub Pages e da Safari su iPhone; i dati restano nel `localStorage` del browser.

## Cosa contiene

- **33 argomenti completi** divisi in 4 aree (cinematica e oscillazioni, lavoro ed energia, sistemi di punti e corpo rigido, fluidi e termodinamica): definizioni, **derivazioni passo-passo** con formule (MathJax), ipotesi di validità, casi limite, errori tipici, intuizione fisica, checklist per l'orale e domande di approfondimento.
- **Simulazioni interattive** (canvas) per costruire l'intuizione: moto armonico, oscillatore smorzato (i tre regimi), risonanza, pendolo semplice (dove l'approssimazione dei piccoli angoli cede), gara dei momenti d'inerzia sul piano inclinato, campo delle velocità nel rotolamento, ciclo di Carnot nel piano p-V e urti. Slider sui parametri fisici e valori aggiornati in tempo reale.
- **Pagina "In parole semplici"**: tutti i 33 argomenti spiegati senza formule, per afferrare l'idea prima della matematica.
- **Piano di studio automatico** fino all'esame: distribuisce gli argomenti sui giorni rimanenti (peso doppio su corpo rigido e termodinamica), riserva gli ultimi 2 giorni a solo ripasso e ridistribuisce ciò che non completi.
- **Simulazione d'orale**: estrazione casuale pesata verso gli argomenti deboli, timer, esposizione a voce, autovalutazione 0–3 sulla checklist e domande finali.
- **Ripasso spaziato (SM-2 semplificato)**: ogni argomento ha uno stato (mai visto → debole → consolidato → padroneggiato) e una data di prossimo ripasso.
- **Formulario stampabile** generato dalle formule chiave, raggruppato per area.

Interfaccia in tema scuro, navigazione a tab in basso su mobile e sidebar su desktop, schede a schermo intero.

## Uso

Nessuna installazione: apri `index.html` nel browser (o il link GitHub Pages qui sopra). Serve la connessione solo al primo caricamento per il rendering delle formule (CDN MathJax).
