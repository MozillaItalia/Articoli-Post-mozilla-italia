# Common Voice ora è in Italiano

Facciamo una piccola premessa su cosa è Common Voice, perché dovresti donare la tua voce e perché ora l'Italiano è disponibile.

Il sito di Common Voice era già stato tradotto in italiano (dalla nostra comunità) qualche mese fà ma mancava il supporto alla lingua italiana ma questo progetto a cosa serve?    
Common Voice https://voice.mozilla.org è un progetto di crowdfunding di Mozilla. Non il classico crowdfounding pensato per raccogliere soldi ma di raccolta di dati in questo caso testuali e vocali basati per lingue specifiche.  
Mozilla ha realizzato un progetto open source di riconoscimento vocale https://github.com/mozilla/DeepSpeech basato su Machine Learning, ovvero ha bisogno di dati reali per poter imparare a riconoscere le varie lingue con le loro parole, pronunce e cosi via.  
Per poter far progredire il progetto ha bisogno di essere nutrito con la partecipazione di volontari che leggono del testo (o che revisionano queste registrazioni) in una lingua. Una volta che ci sono centinaia di letture della stessa frase in una lingua il software si occuperà di trovare le somiglianze.  
Con il trovare le somiglianze ci si riferisce ad un processo di machine learning che imparerà a riconoscere le caratteristiche simili nella frase registrata da più persone con accenti diversi, tono, velocità e pronuncia.  
Queste somiglianze vengono aggregate dal software in un modello, questo schema di riconoscimento dei dati (vocali) permette al software di riconoscere frasi che sente per la prima volta senza avere del testo scritto di riferimento.  
Ovviamente questo modello si basa non su una singola frase ma più frasi che hanno del testo anche in inglese (parole specifiche ad esempio come feedback), sigle (che noi italiani pronunciamo in modo diverso spesso), parole con lettere accentate e così via.  
Questo modello è il prodotto di questo motore (e progetto) che viene reso poi pubblico con tutto il dataset di registrazioni audio (https://voice.mozilla.org/it/data) fornite al progetto sotto licenza libera.

![](https://user-images.githubusercontent.com/403283/42371357-887282ee-810f-11e8-8093-54eeb8cc69f9.png)

## Il supporto dell'italiano

Queste frasi che vengono lette o revisionate dai partecipanti su base volontaria hanno richiesto molto lavoro dalla nostra comunità. Abbiamo partecipato allo sprint https://voice-sprint.mozilla.community/ organizzato da Mozilla in Maggio ma il materiale non era sufficiente per sbloccare la lingua sul portale.  
Queste frasi devono essere di pubblico dominio, Creative Commons zero o con il permesso degli autori e devono essere 5000 per poter sbloccare la lingua e noi italiani abbiamo lanciato il supporto alla nostra lingua con oltre 7700 frasi (ad oggi).  
Queste frasi sono state estratte da diversi materiali, per poter aggregare diverse tipologie di testo:

* Manualistica di traduzione (ad esempio il nostro manuale di traduzione https://mozillaitalia.gitbooks.io/l10n-guide/it/)
* Manualistica di informatica (ad esempio materiale del Team per la Trasformazione digitale o nostri articoli)
* Testi religiosi (discorsi dei papi del '900)
* Libri gialli (di pubblico dominio)
* Racconti fantasy/sci-fi
* Tesine delle superiori
* Temi scolastici
* Modi di dire e scioglilingua 
* Resoconti di eventi (scritti dai nostri volontari)
* Canti popolari 
* Materiale sportivo
* Estratti di messaggi scambiati via chat
* Documenti di stampo manageriale (estratti di riunioni ad esempio)

Tutto questo materiale poi è stato revisionato per errori grammaticali, doppioni e per accorciare le frasi (sul portale c'é un tetto massimo per la lunghezza delle registrazioni audio).  
Queste frasi quindi sono un lavoro di raccolta, pulizia e revisione per verificare la loro qualità, che fossero di pubblico dominio e che non contenessero materiale privato.

Naturalmente possono esserci degli errori e per questo vi invitiamo a segnalarceli sul forum (https://forum.mozillaitalia.org/index.php?topic=71027.msg492854) oppure facendo una pull request sul nostro fork su GitHub (https://github.com/MozillaItalia/voice-web/blob/ita-review/server/data/it/frasi.txt).  
Al momento non stiamo raccogliendo altre frasi ma preferiamo focalizzarci a migliorare il materiale esistente prima di aumentarlo nuovamente altrimenti diventa difficile gestirlo.

## Perché partecipare

Realizzare un modello della lingua italiana che sia libero da qualunque licenza commerciale, richiesta di internet e affidato a terzi ci permette di mantenere: sicurezza, privacy ed estendibilità senza limiti.  
Per questo motivo Mozilla ha realizzato questo progetto, il dataset della lingua inglese è stato già reso disponibile (con il modello incluso) che contiene oltre 1000 ore di registrazione fatte da 20000 volontari diversi (https://blog.mozilla.org/blog/2017/11/29/announcing-the-initial-release-of-mozillas-open-source-speech-recognition-model-and-voice-dataset/). Questo modello è liberamente utilizzabile per progetti educativi ad esempio o per progetti personali ed ha un errore minore del 10%, per approfondire questo aspetto vi invitiamo a leggere l'articolo ufficiale https://hacks.mozilla.org/2017/11/a-journey-to-10-word-error-rate/.  
Ci sono progetti open source, ad esempio https://mycroft.ai/, che può essere utilizzato sul proprio computer oppure con il dispositivo ufficiale oppure realizzato da sé per avere un Alexa che sia libero. Questo progetto si basa sulla tecnologia di Mozilla che è già integrata di base.  
Ci sono dei progetti sperimentali come https://xaero.app/ per realizzare un correttore grammaticale basato sul modello che permette di essere ancora più accurati oppure un Text-to_speech ovvero di lettore del testo https://github.com/mozilla/tts.  
Una delle altre opportunità per gli sviluppatori sono anche le raccolte stesse di frasi di pubblico dominio che possono essere utilizzate anche per altre tipologie di machine learning e sono accessibili su https://github.com/mozilla/voice-web/tree/master/server/data.

Come si può vedere da un progetto di raccolta dati che sia libero abbiamo già diversi esempi di altrettanti progetti liberi!  
Questi progetti sono basati sull'inglese ma con la disponibilità dell'italiano e di altre lingue come lo Sloveno, Francese o Turco si aprono opportunità di trasparenza e di parità nella tecnologia di riconoscimento vocale.

## Come partecipare

Registrando un profilo sul sito https://voice.mozilla.org/it/languages sarà possibile tracciare quanto è stato fatto altrimenti rimarrà anonimo.  
Sfruttando la nuova interfaccia del portale rilasciata da poco ci saranno due tipi di attività (che si possono fare anche da mobile).  
Per partecipare non è necessario installare nessuno software se usare il browser ed abilitare i permessi per il microfono al sito.

### Parla

![](https://user-images.githubusercontent.com/403283/42370763-e332a15c-810d-11e8-8863-ad82b806576e.png)

Da questa interfaccia sarà possibile registrare un file audio leggendo il testo che è visualizzato. Sarà possibile riascoltare la registrazione ed approvarla caricandola.

### Ascolta

![](https://user-images.githubusercontent.com/403283/42370811-078ce1f2-810e-11e8-9a62-7eb41b91e8e7.png)

Da questa interfaccia invece si potranno ascoltare le registrazioni fatte da altri e poterle approvare o rifiutare, ad esempio non è stata pronunciata correttamente una parola o è troppo veloce. Questa attività è ideale da fare quando non si può parlare ma si può ascoltare (ad esempio in cuffia).

### Scorciatoie

Ci sono anche le scorciatoie da tastiera per non dover utilizzare il mouse, ad esempio *P* per mettere in pausa o ascoltare o *S* per saltare la registrazione.

## Quando sarà disponibile il modello Italiano

Il piano di Mozilla è di rilasciare i modelli per ogni lingua verso Dicembre ma questo sarà possibile solo se ci sono tante registrazioni e tanti partecipanti. La qualità del riconsocimento vocale sta a noi!  

## Voglio promuovere il progetto, come posso fare?

Fantastico! Se utilizzi Telegram vieni a conoscere la comunità su https://t.me/mozItaHUB, specialmente sul canale Voglio diventare un volontario.  
Troverai membri della comunità italiana che potranno rispondere alle tue domande e fornirti idee per promuovere il progetto.  

Il lancio in Italiano è corrisposto con un evento a Torino:

https://twitter.com/astrastefania/status/1014929254612598784

Ma non ci fermiamo qui, il prossimo evento sarà https://www.ihc.camp/ dove Mozilla Italia avrà un gazebo, diversi talk e anche diversi volontari presenti! Stiamo ancora definendo i dettagli ma probabilmente faremo una raccolta punti che a seconda del volume delle attività effettuate su Common Voice (e di altro tipo) sarà possibile ottenere gadget specifici (da adesivi a magliette).

Ringraziamo tutti quelli che hanno partecipato nelle varie fasi del progetto per arrivare al risultato di oggi: Edoardo, Giorgio, Simone, Saverio, Daniele, Irene, Giovanni, Sara, Francesco, Stefania e i tanti altri tra omonimi a quelli che ci hanno solo spronato nel progetto.