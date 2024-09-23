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

## But what about diabetes?

Of course, as soon as you test and dial-in all these things, diabetes will throw you a curve ball and change your insulin needs.  That’s the way it works.  It’s not just YDMV (your diabetes may vary), it’s actually YDWV (your diabetes will vary).  So how do you adjust settings without needing to open loop every time?  Short answer: it takes practice.

For us personally, hormones play the largest variable in settings.  If we estimate average basal rate of about 1 u/hr for Anna, hormones can make her range from 0.55 to 3 u/hr.  Illness or heat can make her ISF change from typical 35 to a range between 30-45.  We have gotten used to changing settings (basal rates mostly) to accommodate hormone fluctuations.  Illness and heat we tend to use shorter-term fixes like temp targets to help rather than changing settings.

One of the easiest tells we have that basals need to change is hanging out above/below target with positive/negative IOB.  Here’s one recent example.  During the day before this screenshot, Anna was busy with some stressful things at school…like being front and center during the school’s pep rally for Homecoming around noon to 2pm.  So, the unusual red spot on her graph didn’t immediately make me think anything was “wrong”.  Then she went to Homecoming dance that night, hung a little higher than target, but nothing too bad and she wasn’t looping during dance (her choice).  She came home around midnight, and at about 5am I noticed that she was hanging out steady at about 130s and carrying positive IOB.  Fingerstick showed she was at 195 (thanks Dexcom).  Gave a correction and started to wonder if may her basals were too low, because she shouldn’t have been that high under normal operations (but maybe homecoming dance was to blame?).  I didn’t make any changes to her settings at this point, but did start to watch for signs.

![](../images/first.png)

In the morning, Anna had a typical breakfast with some toast and fruit.  With fiasp, she hasn’t really been going above 150 (and usually not above 130)…so when she hit nearly 180 for the meal, I definitely started to think basals may indeed be low…but I waited to see how the meal would land.

![](../images/second.png)

As you can see above, about 2.5 hours after her meal of fairly quick carbs, she started to rise.  And she started to rise with about 0.75 units IOB.  This is odd for her.  Ideally, we wouldn’t be seeing sharp, steady rises with a good amount of IOB.  Additionally, this meal didn’t have protein or fat involved so I knew the rise wasn’t a late food contribution (even if Loop had some cob still on board).

So, once it looked like (1) the rise really wasn’t slowing down even like Loop thought it should, (2) she was climing with fiasp for nearly an hour of high temping with (3) positive IOB…then I finally decided to adjust basals.  I moved her basals from 0.85 to 1.2 u/hr.  Why that number?  A guess based on basal rates she tends to move between during her regular variations.  Trial and error have shown us that a rate slightly above 1 u/hour is usually needed sometimes.

![](../images/third.png)

One of the things I like to watch is the IOB pill when we make a basal change.  Ideally, I like to get the IOB back to a number that is roughly how much I think may help get a correction going again.  So, changing the basals from 0.85 to 1.2, Loop recalculated IOB from 0.52 to -0.48.  Which was roughly in line with what I’d expect…Anna was about 27 mg/dl over her 95 mg/dl target with an ISF of 55…meaning she’d need about 0.49 units to correct to target.  Perfect…seemed like a reasonable amount of movement for basals then.  Loop started running a high temp and I wait to see how things look in about 2 hours.

![](../images/fourth.png)

About 1.5 hours later, Anna wasn’t quite coming down as fast as I would’ve expected. She was still holding 0.57 IOB and at same BG as she was 80 minutes before.  So…I waited a bit and adjusted again to 1.4 u/hour.  Again, just a guess, but nearly two hours after that adjustment we are sitting just about at target and just about even IOB.  I’ll probably split the baby and use 1.3 u/hr going forward.

So…that’s how I look for and make tweaks to my settings while closed looping.  The basis is knowing what “good” times look like and how foods normally behave.  Open-loop testing really helps with that.  Then, when you find yourself with some of the telltale signs (food going differently than expected, BGs holding steady but not at target, moving up/down without IOB helping, etc) over an extended period of time, you can make small adjustments and watch for the resulting behaviors.  I don’t adjust based on just one meal or one period of above-target BGs.  There’s too often another reason (stress, sensor issues, etc) that could explain a short term high/low BG pattern…but if I notice the trend continuing for a period of time/several meals, I adjust.  Shorter term issues from stress or exercise we deal with using temp targets or just have a little more patience and wait for them to come down when the issue has passed.
