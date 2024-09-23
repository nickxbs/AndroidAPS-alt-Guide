# Ottimizzazione del Tuo Sistema

Questo è un adattamento di un articolo del blog di Katie DiSimone. Puoi trovare l'originale [qui](http://seemycgm.com/2017/10/29/fine-tuning-settings/)

È assolutamente vero che non esiste un unico posto dove leggere Come Regolare le Tue Impostazioni in qualsiasi documento sul looping. Il motivo è... le risposte sono fondamentalmente le stesse di altre situazioni non di looping... testare i basali, testare i rapporti insulina-carboidrati, testare le sensibilità all'insulina. La difficoltà è che una volta che le persone stanno già utilizzando il loop, nessuno vuole spegnerlo per testare di nuovo le impostazioni. Tutti vogliono semplicemente regolare le impostazioni al volo mantenendo anche un loop chiuso. Quindi... cercherò di spiegare un po' entrambi i metodi.

Prima di iniziare, permettetemi di dire questo nel caso non fosse ovvio... Non sono il tuo medico, né il medico di nessun altro. Non prendere le mie parole come sostituto delle conversazioni con il tuo medico.

Ok... fornito questo avvertimento... [Think Like a Pancreas](https://www.amazon.co.uk/Think-Like-Pancreas-Practical-Insulin-Completely/dp/0738215147) è un ottimo riferimento per comprendere alcuni dei principi guida nella terapia con microinfusore. Permettetemi di riassumere le parti importanti:

- I tassi basali dovrebbero mantenere i tuoi livelli di glicemia stabili in assenza di altre influenze (come cibo, farmaci, ecc.).
- I boli dovrebbero riportare i tuoi livelli di glicemia all'obiettivo dopo un pasto.
- L'ISF dovrebbe essere la quantità di cui una unità di insulina abbassa i tuoi livelli di glicemia senza altre influenze.

Se sei nuovo nel looping, ti consiglio di pianificare un momento per ritestare/reimpostare tutte le tue supposizioni sulle impostazioni del tuo diabete. Mantieni una mente aperta se vuoi mantenere un loop chiuso. (com'è questa per una frase ad effetto?)

È assolutamente possibile avere due impostazioni sbagliate che sembrano una impostazione giusta quando si bilanciano. Il problema è che quelle impostazioni sbagliate non si bilanceranno in tutte le situazioni. Esempio: Basali troppo bassi possono essere compensati mangiando regolarmente pasti con un rapporto insulina-carboidrati troppo forte. Se però smetti di mangiare, inizierai ad andare alto perché quell'insulina extra dai boli dei pasti non sarà lì ad aiutare la mancanza di basali. Prendersi il tempo di validare le tue impostazioni testandole veramente è una pratica davvero buona.

## 1°: Durata dell'Insulina

Il problema numero uno delle impostazioni dei nuovi looper sarà probabilmente una durata dell'azione dell'insulina (DIA) troppo breve. Quasi tutti noi abbiamo tagliato il nostro DIA a circa 3 ore nella terapia tradizionale con microinfusore. C'è una ragione per questo. Nell'uso tradizionale del microinfusore, il DIA viene utilizzato solo per calcolare l'IOB residuo in qualsiasi momento dopo un bolo. Questo è tutto. E quando usiamo l'IOB residuo nella terapia tradizionale con microinfusore? Di solito quando vogliamo dare una correzione perché una glicemia è bloccata alta o sta andando bassa... in altre parole, il DIA viene utilizzato come approssimazione grossolana per correggere le glicemie fuori obiettivo. Non deve essere una scienza missilistica quindi... stiamo facendo un'approssimazione perché alcuni altri numeri (conteggio dei carboidrati, basali, ecc.) non si stavano comportando come ci aspettavamo e quindi portavano a una glicemia fuori obiettivo.

Ma nel looping, il DIA (e il relativo IOB) gioca una parte ENORME in come il loop sta anticipando e valutando il movimento della tua glicemia. L'IOB viene utilizzato letteralmente ogni singolo minuto per ogni singolo calcolo del loop per determinare dove andare successivamente nell'impostazione di un basale temporaneo o nel fornire una raccomandazione di bolo.

Non solo, ma anche la FORZA dell'insulina in un dato momento viene utilizzata. I loop chiusi sanno e si preoccupano se la tua insulina è stata somministrata di recente e deve raggiungere il picco presto (come tra 60-90 minuti con novolog/humalog), o se è nella lenta fase di coda ore dopo dove gli impatti sulla glicemia saranno molto meno drammatici. Quindi, il DIA significa molto nel tuo mondo di loop chiuso.

Cosa succederà se usi un DIA troppo breve nel loop chiuso? Lo vedrai in vari modi, ma un DIA troppo breve darà l'equivalente di un accumulo di insulina. I loop assumeranno che l'insulina stia scomparendo più velocemente di quanto in realtà faccia. Se stai ottenendo glicemie stabili mentre fai il loop chiuso con un DIA breve, è probabile che i tuoi basali siano impostati troppo bassi per compensare. Se invece hai impostato correttamente i tuoi basali e usi un DIA breve nel loop chiuso, probabilmente ti troverai ad andare basso a causa delle correzioni. Una buona indicazione di questo è andare più basso dell'obiettivo portando IOB negativo da precedenti basali temporanei bassi/zero del loop.

Raccomandazione generale: Imposta il tuo DIA a 5 o 6 ore per novolog/humalog, non continuare a usare il tuo vecchio DIA breve dai giorni della terapia tradizionale con microinfusore. Se stai usando le versioni più recenti di Loop o OpenAPS, il codice è predefinito per 6 ore. Testa i tuoi basali (vedi sotto) con il nuovo DIA più lungo e assicurati di poter ottenere glicemie stabili con i nuovi basali.

## 2°: Basali

Ora che hai impostato un DIA ragionevole, assicurati di testare i tuoi basali. Personalmente, troviamo che testare i basali possa essere abbastanza indolore e non richiede giorni di digiuno. Invece, cerchiamo opportunità facili. Se sei disposto a testare in loop aperto, questo darà le informazioni più accurate nel modo più rapido.

È un test abbastanza facile. Spegni il tuo loop. Non mangiare cibo, non fare esercizio pazzo, non sederti in una vasca idromassaggio. Basta avere un periodo di tempo medio rilassante e vedere se i tuoi basali sono in grado di mantenerti più o meno stabile. Non importa se sei all'obiettivo o no... l'idea è semplicemente di non avere insulina extra a bordo da boli o correzioni e osservare cosa succede durante quelle ore. In genere ci piace vedere circa due ore di glicemie senza l'influenza di boli alimentari.

Credimi quando dico che Anna non è entusiasta del test basale a digiuno... quindi cerco opportunità per renderlo meno ingombrante. Per esempio, uso un pasto che so come il palmo della mia mano come dosare per esso e che generalmente non ha bisogno di correzioni. Per noi... sono due uova strapazzate extra large (o tre piccole) con formaggio dosate a 8g. Se mangia quel pasto, la risposta della glicemia è lenta e misurata e 3 ore dopo quel pasto... gli effetti del bolo e del cibo sono davvero attenuati e possiamo iniziare a osservare se le glicemie rimangono abbastanza stabili per le successive due ore.

Per esempio, ecco alcuni dei recenti test basali in loop aperto che abbiamo fatto con Anna... confermato che le glicemie potevano rimanere abbastanza stabili senza il coinvolgimento dell'aiuto del basale temporaneo dal looping. Gli 8g di uova alla fine di quasi 3 ore... sembra che sia andata un po' più bassa (e potrebbe essere diminuita ancora di più se non avesse iniziato il pasto successivo) di quanto aveva iniziato. Poiché i basali sembravano mantenerla abbastanza stabile, ho preso nota mentalmente che il rapporto insulina-carboidrati potrebbe essere un po' troppo forte, ma non ho regolato subito. Ho aspettato di vedere come si sarebbe comportato il pasto successivo.

![Basale Loop Aperto](../images/basal-open-loop.png)

Se assolutamente non vuoi spegnere il tuo loop chiuso per testare questo... vedi se riesci a trovare un momento in cui le glicemie sono stabili, sei all'obiettivo o vicino, e non stai portando IOB positivo o negativo. Se non riesci a trovare un momento del genere, è probabile che tu possa aver bisogno di regolare le impostazioni. La notte è di solito il momento più facile da trovare... ma avere basali notturni ben impostati non significa necessariamente che anche il giorno sia ben impostato. Anche questo deve essere testato.

## 3°: Fattore di Sensibilità all'Insulina

Il fattore di sensibilità all'insulina (ISF) è la prossima impostazione logica da testare. Se hai appena fatto il test basale e ottenuto glicemie stabili con un loop aperto... prova a prendere una o due compresse di glucosio. Aspetta che le tue glicemie siano stabili alla glicemia più alta, e dai una correzione sicura che pensi ti porterà vicino all'obiettivo. Osserva la conseguente caduta della glicemia nelle successive 2-3 ore. Dovresti vedere le glicemie tornare a un livello stabile. Di quanto è scesa la glicemia? Quante unità di insulina hai usato? Dividi i due numeri e avrai il tuo ISF. Se la tua glicemia è scesa di 15 mg/dl con mezza unità di insulina, il tuo ISF è approssimativamente 30 mg/dl/unità.

Nel contesto di un loop chiuso, l'ISF influenza quanto fortemente il loop risponde alle deviazioni dall'obiettivo. Se il tuo numero ISF è troppo alto, allora non risponderà abbastanza fortemente per riportarti in linea. Un numero troppo piccolo e la risposta sarà troppo forte e oscillerà tra basali temporanei zero e alti. E vedrai una glicemia fluttuante come risultato.

Se il tuo numero ISF è troppo basso (l'insulina sta avendo un effetto maggiore di quanto il numero suggerirebbe), uno dei sintomi più comuni che vedrai è un'altalena di glicemie dove i basali temporanei stanno ciclando tra zero e alti. Prenderò in prestito un paio di grafici di esempio dal gruppo Looped. Questi sono esempi in cui un ISF troppo basso (numero ISF troppo piccolo) è più che probabilmente un grande fattore nell'altalena (non significa che sia l'unico colpevole, ed è più difficile da individuare quando il cibo è coinvolto come nel secondo grafico). Ma, basali temporanei alti a fulmine seguiti da cadute di glicemia molto rapide e temp zero è di solito un ISF troppo basso... aumenta il numero ISF per aiutare il looping a sapere che ogni unità di insulina sta effettivamente facendo più abbassamento della glicemia.

![](../images/19248027_10155510691426450_4212861104795372164_n.jpg)
![](../images/15591479_10154031400407115_2525671186696153617_o.jpg)
![](../images/Screen-Shot-2017-10-28-at-12.20.02-PM.png)

## 4°: Rapporti Insulina-Carboidrati

Ora che hai impostato basali, ISF e DIA... ecco dove diventa davvero tentante chiudere il loop e andare avanti. E, sinceramente, non è così difficile testare i rapporti insulina-carboidrati su un loop chiuso vs un loop aperto se hai testato solidamente tutti questi altri fattori.

Un buon rapporto insulina-carboidrati riporterà le tue glicemie al punto di partenza del pasto entro circa 3 ore o giù di lì.

Un cattivo rapporto insulina-carboidrati ti lascerà più alto o più basso del punto di partenza del pasto.

Per esempio, questi sono due esempi di rapporti insulina-carboidrati troppo forti. In questo primo esempio, ci sono 2,27 unità di IOB e le glicemie sono a 103 e stanno scendendo a un ritmo abbastanza buono a circa 2 ore dopo il pasto. Se il pasto successivo non fosse stato mangiato allora, sicuramente sarebbe stato necessario un trattamento per l'ipoglicemia.

![](../images/carbratio1.jpg)

Questo prossimo grafico mostra anche un rapporto insulina-carboidrati troppo aggressivo. Tre ore dopo il pasto, c'è quasi 0,50 unità di IOB, la glicemia è ben al di sotto di dove il pasto è iniziato, e sicuramente sono necessari trattamenti per l'ipoglicemia.

![](../images/carbratio2.png)

Se trovi che un rapporto insulina-carboidrati corretto sta producendo buone glicemie 3 ore dopo, ma non sei soddisfatto dei picchi di glicemia durante il pasto... allora potrebbe essere il momento di esplorare l'aumento o l'aggiunta di tempo di pre-bolus al tuo pasto o l'implementazione di obiettivi "mangiare presto" un'ora prima dei pasti per aiutare a controllare il picco di glicemia post-pasto. Rafforzare artificialmente i rapporti insulina-carboidrati per aiutare a controllare il picco di glicemia post-pasto probabilmente produrrà ipoglicemie 2-3 ore dopo un pasto.

## Ma cosa dire del diabete?

Naturalmente, non appena testi e metti a punto tutte queste cose, il diabete ti lancerà una palla curva e cambierà il tuo fabbisogno di insulina. È così che funziona. Non è solo YDMV (your diabetes may vary - il tuo diabete può variare), è in realtà YDWV (your diabetes will vary - il tuo diabete varierà). Quindi come si regolano le impostazioni senza dover aprire il loop ogni volta? Risposta breve: ci vuole pratica.

Per noi personalmente, gli ormoni rappresentano la variabile più grande nelle impostazioni. Se stimiamo una velocità basale media di circa 1 u/h per Anna, gli ormoni possono farla variare da 0,55 a 3 u/h. La malattia o il caldo possono far cambiare il suo ISF da un tipico 35 a un intervallo tra 30-45. Ci siamo abituati a cambiare le impostazioni (principalmente le velocità basali) per adattarci alle fluttuazioni ormonali. Per la malattia e il caldo, tendiamo a usare correzioni a breve termine come obiettivi temporanei per aiutare piuttosto che cambiare le impostazioni.

Uno dei segnali più facili che abbiamo che i basali devono cambiare è il rimanere sopra/sotto l'obiettivo con IOB positivo/negativo. Ecco un esempio recente. Durante il giorno prima di questo screenshot, Anna era impegnata con alcune cose stressanti a scuola... come essere al centro dell'attenzione durante il raduno di incoraggiamento della scuola per il Homecoming dalle 12 alle 14 circa. Quindi, il punto rosso insolito sul suo grafico non mi ha fatto pensare immediatamente che qualcosa fosse "sbagliato". Poi è andata al ballo di Homecoming quella sera, è rimasta un po' sopra l'obiettivo, ma niente di troppo grave e non stava facendo il loop durante il ballo (sua scelta). È tornata a casa intorno a mezzanotte, e verso le 5 del mattino ho notato che si stava mantenendo stabile intorno ai 130 e portava un IOB positivo. Il controllo con il pungidito ha mostrato che era a 195 (grazie Dexcom). Ho dato una correzione e ho iniziato a chiedermi se forse i suoi basali fossero troppo bassi, perché non avrebbe dovuto essere così alta in condizioni normali (ma forse era colpa del ballo di Homecoming?). Non ho fatto alcun cambiamento alle sue impostazioni a questo punto, ma ho iniziato a cercare segni.

![](../images/first.png)

Al mattino, Anna ha fatto una tipica colazione con un po' di toast e frutta. Con il fiasp, non è davvero andata sopra i 150 (e di solito non sopra i 130)... quindi quando ha raggiunto quasi 180 per il pasto, ho definitivamente iniziato a pensare che i basali potessero essere effettivamente bassi... ma ho aspettato per vedere come si sarebbe stabilizzato il pasto.

![](../images/second.png)

Come puoi vedere sopra, circa 2,5 ore dopo il suo pasto di carboidrati abbastanza rapidi, ha iniziato a salire. E ha iniziato a salire con circa 0,75 unità di IOB. Questo è strano per lei. Idealmente, non dovremmo vedere aumenti bruschi e costanti con una buona quantità di IOB. Inoltre, questo pasto non conteneva proteine o grassi, quindi sapevo che l'aumento non era un contributo tardivo del cibo (anche se Loop aveva ancora alcuni carboidrati a bordo).

Quindi, una volta che sembrava che (1) l'aumento non stesse davvero rallentando nemmeno come Loop pensava che dovesse, (2) stava salendo con fiasp per quasi un'ora di temping alto con (3) IOB positivo... allora ho finalmente deciso di aggiustare i basali. Ho spostato i suoi basali da 0,85 a 1,2 u/h. Perché quel numero? Una stima basata sulle velocità basali tra cui tende a muoversi durante le sue variazioni regolari. Prove ed errori ci hanno mostrato che a volte è necessaria una velocità leggermente superiore a 1 u/ora.

![](../images/third.png)

Una delle cose che mi piace osservare è la pillola IOB quando facciamo un cambiamento basale. Idealmente, mi piace riportare l'IOB a un numero che è all'incirca quanto penso possa aiutare a far partire di nuovo una correzione. Quindi, cambiando i basali da 0,85 a 1,2, Loop ha ricalcolato l'IOB da 0,52 a -0,48. Il che era più o meno in linea con quello che mi aspettavo... Anna era circa 27 mg/dl sopra il suo obiettivo di 95 mg/dl con un ISF di 55... il che significa che avrebbe avuto bisogno di circa 0,49 unità per correggere all'obiettivo. Perfetto... sembrava una quantità ragionevole di movimento per i basali allora. Loop ha iniziato a eseguire un temp alto e aspetto di vedere come vanno le cose tra circa 2 ore.

![](../images/fourth.png)

Circa 1,5 ore dopo, Anna non stava scendendo così velocemente come mi sarei aspettato. Aveva ancora 0,57 IOB e la stessa glicemia di 80 minuti prima. Quindi... ho aspettato un po' e ho aggiustato di nuovo a 1,4 u/ora. Di nuovo, solo una supposizione, ma quasi due ore dopo quell'aggiustamento siamo seduti proprio all'obiettivo e con IOB quasi in pari. Probabilmente dividerò la differenza e userò 1,3 u/h andando avanti.

Quindi... ecco come cerco e faccio aggiustamenti alle mie impostazioni mentre sono in loop chiuso. La base è sapere come appaiono i "buoni" momenti e come si comportano normalmente i cibi. Il test in open-loop aiuta davvero con questo. Poi, quando ti trovi con alcuni dei segnali rivelatori (cibo che si comporta diversamente dal previsto, glicemie che rimangono stabili ma non all'obiettivo, che si muovono su/giù senza che l'IOB aiuti, ecc.) per un periodo di tempo prolungato, puoi fare piccoli aggiustamenti e osservare i comportamenti risultanti. Non regolo in base a un solo pasto o un solo periodo di glicemie sopra l'obiettivo. Troppo spesso c'è un'altra ragione (stress, problemi del sensore, ecc.) che potrebbe spiegare un pattern di glicemie alte/basse a breve termine... ma se noto che la tendenza continua per un periodo di tempo/diversi pasti, faccio aggiustamenti. Problemi a breve termine dovuti a stress o esercizio li affrontiamo usando obiettivi temporanei o semplicemente avendo un po' più di pazienza e aspettando che si risolvano quando il problema è passato.
