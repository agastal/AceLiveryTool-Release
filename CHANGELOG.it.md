# Novità

## [0.6.0] - 2026-10-19

Fibra di carbonio, loghi SVG, e immagini che si ridimensionano e ruotano direttamente sull'auto.

### Novità
- Pennello **Fibra di carbonio** (e punta **Carbonio**): dipinge una trama di fibra di carbonio nel colore del
  pennello (grigio scuro per il carbonio classico); **Grana** regola la larghezza di un filo. Con la punta Carbonio,
  **Riempi col colore del pennello** riempie il livello di carbonio: con lo strumento **Parti**, un cofano in carbonio
  in due clic.
- File **SVG** per **+ Immagine**, **+ Texture** e i timbri del pennello (**Carica…**): i loghi restano nitidi a
  qualsiasi dimensione, e i progetti conservano l'SVG stesso.
- Strumento **Posiziona**: **Maiusc** + trascina sull'auto ridimensiona l'immagine o il testo selezionato, **Ctrl** +
  trascina lo ruota (premendo anche Maiusc, a passi di 15°). Ognuno è un passo di **Annulla**.

### Modifiche
- Durante la preparazione delle auto dal gioco (**Prepara le auto dal gioco**) una rotellina e la clessidra
  mostrano che il lavoro è in corso.

### Correzioni
- Dove un pezzo piccolo (per esempio una targa) condivide la texture con un pannello, pennello, gomma e sfumatura
  ora dipingono il pannello invece di mancarlo.
- Il suggerimento sotto lo strumento **Posiziona** lo chiamava con un altro nome.

## [0.5.0] - 2026-10-18

Testo curvo, un pennello che si vede e niente più lavoro perso.

### Novità
- Il testo si può curvare come in Illustrator: nel livello di testo, **Curvatura** (**Arco**, **Arcata**,
  **Rigonfiamento**, **Bandiera**) e **Piega**, da -100% a 100% (in negativo piega dall'altra parte).
- Il pennello e la gomma mostrano un cerchio sotto il puntatore, largo quanto il **Raggio** (due con la **Simmetria
  sinistra/destra**); sopra l'auto prende il posto del puntatore del mouse.
- **Modifiche non salvate**: prima di chiudere la finestra, iniziare un progetto **Nuovo**, aprirne un altro o
  cambiare auto, l'app chiede se **Salvarle**.

### Modifiche
- Il suggerimento su mouse e viste compare solo con lo strumento **Vista**; quello sulla linea dritta con
  **Maiusc + clic** ora è sotto le impostazioni del pennello.

### Correzioni
- Spostando uno slider (per esempio il **Raggio**) il valore non va più a capo spostando tutto il pannello.

## [0.4.0] - 2026-10-17

Linee dritte e sfumature.

### Novità
- Strumento **Sfumatura** (G): trascina sull'auto da dove comincia a dove finisce, e il livello di pittura
  selezionato si riempie dal colore **Da** al colore **A**, o **Fino a trasparente**. **Lineare** o **Radiale**, con
  la sua **Opacità** e la **Simmetria sinistra/destra**; mentre trascini la vedi sull'auto. Sulla maschera del
  livello, fa sfumare via il livello.
- Linee dritte: col pennello o la gomma, **Maiusc + clic** traccia una linea dritta dalla fine dell'ultimo tratto;
  tieni premuto per vedere la linea mentre la sposti.

## [0.3.0] - 2026-10-17

Pennelli pronti, tavolette grafiche e uno schermo più ordinato.

### Novità
- Menu **Pennello** con dieci pennelli pronti, ognuno con un'anteprima: tondo duro, tondo morbido, spruzzo, gesso,
  setole, pennarello, pennino calligrafico, schizzi, puntinato, stelle. Impostano la punta e le sue variazioni; colore,
  raggio e opacità restano come sono. L'ultimo scelto viene ricordato.
- Nuova punta **Gesso** e i timbri **Setole**, **Pennarello** e **Pennino**.
- Tavolette grafiche: il raggio segue la pressione della penna (**Il raggio segue la pressione della penna**,
  **Raggio minimo**). Queste impostazioni compaiono dopo il primo tocco della penna; il mouse dipinge sempre al raggio
  pieno.
- Menu **Vista**: **Vista UV** (tasto U) e le viste **Davanti**, **Lato** e **Sopra**.

### Modifiche
- **Carrozzeria** / **Vetri** ed **Esporta nel gioco…** ora sono nella barra in alto.
- Si dipinge molto più veloce sui portatili con due schede grafiche: l'app ora usa quella dedicata.
- I pennelli fitti (spruzzo, puntinato, stelle) dipingono veloci come gli altri.
- Icona nuova.

## [0.2.0] - 2026-10-16

Dipingere una parte dell'auto alla volta: il cofano, una portiera, un paraurti, con un clic.

### Novità
- Strumento **Parti** (P): clicca una parte dell'auto e il livello selezionato si vede solo lì (il primo clic gli
  crea una maschera); Maiusc+clic nasconde di nuovo una parte. **Parte intera** prende tutta la portiera, il cofano o
  il paraurti come li muove il gioco; **Anche l'altro lato** prende la parte corrispondente dall'altro lato. La barra
  di stato dice il nome della parte sotto il puntatore. Poi riempimento, pennello, immagini e testi di quel livello
  restano dentro.
- Le auto vengono preparate di nuovo da sole, una volta, quando una nuova versione dell'app ha bisogno di più
  informazioni (questa legge le parti delle auto): circa un minuto al primo avvio dopo l'aggiornamento.

### Modifiche
- I pulsanti degli strumenti (Vista, Pennello, Gomma, Posiziona, Parti) sono icone; nomi e tasti sono nei
  suggerimenti.

## [0.1.0] - 2026-10-16

La prima versione pubblica: un editor 3D di livree per tutte le auto di Assetto Corsa EVO.

### Novità
- Tutte le 71 auto del gioco, preparate dalla tua installazione al primo avvio (circa un minuto), con le ruote
  e il layout UV come livello guida.
- Livelli con maschere, modi di fusione e rugosità, metallo e clear coat propri.
- Pennelli che dipingono in 3D, anche a cavallo dei pannelli senza cuciture: tondo, spray e timbri, con
  simmetria sinistra/destra.
- Immagini e testi posizionati sull'auto, anche specchiati sull'altro lato.
- Annulla e ripeti; file di progetto (`.acelivery`).
- Viste allineate agli assi dell'auto, come in Blender: 1, 3, 7 per fronte, lato destro e sopra (con Ctrl le
  opposte), oppure Alt + trascina sull'auto.
- Export nel gioco come External Livery, collegata a un'auto del tuo garage: l'app elenca le auto salvate con il
  loro allestimento, avvisa degli allestimenti che non accettano livree esterne e di un'auto già collegata a
  un'altra livrea.
- *File → Gestisci le livree…*: tutte le External Livery con anteprima, la loro auto e se il gioco le ha mai
  applicate; apri la cartella, disattivala e riattivala, spostala nel Cestino o **Modificala**: qualunque External Livery, anche non fatta
  con l'app, si apre sulla sua auto come livello con i suoi colori e materiali, pronta da ridipingere e riesportare.
- Italiano, inglese, francese, tedesco e spagnolo.
