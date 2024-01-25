# PsyDocFinder
Benvenuti in PsyDoc Finder, l'app definitiva per il tuo benessere mentale.<br>
Siamo qui per aiutarti a trovare la giusta via verso la salute mentale.<br>
Registrati come utente o specialista, accedi con facilità.<br>
Scopri chi siamo e come contattarci nella nostra breve introduzione.<br>
Gli utenti possono cercare specialisti in base alle proprie esigenze, grazie alla nostra funzione di ricerca avanzata.<br>
I specialisti, iscritti all'albo, possono creare il loro profilo, con dettagli su di loro, orari di ricevimento e tariffe.<br>
Il nostro calendario ti permette di gestire gli appuntamenti in modo semplice, con pop-up per ricordarti le tue sedute.<br> 
Abbiamo anche una sezione dedicata alla psicoeducazione, per comprendere meglio la salute mentale e i segnali d'allarme.<br>
La tua sicurezza è importante: abbiamo una sezione di pronto soccorso per situazioni di emergenza e numeri d'emergenza disponibili.<br> 
Gli utenti possono condividere le proprie esperienze e recensioni sui specialisti e il sito, ma solo dopo aver effettuato almeno una seduta.<br> 
I specialisti possono leggere e condividere le recensioni di altri specialisti che utilizzano il sito per il lavoro.<br>


## Requisiti funzionali:

1) Login iniziale come utente o specialista:<br>
	Attori:	Utenti, Specialisti.<br>
	Descrizione: login differenziato per utenti e specialisti, si puo effetuare il login come specialista solo se si è iscritti all'albo.

2) Introduzione su chi siamo:<br>
	Attori: Utenti, Specialisti.<br>
	Descrizione: Tendina che permette di visualizzare una breve introduzione su chi sono gli sviluppatori del sito, su come conttattarci ed i nostri vari social media.

3) Ricercare i vari specialisti:<br>
	Attori: Utenti.<br>
	Descrizione: Permettere la ricerca all'utente per campi di uno specialista.

4) Crea profilo:<br>
	Attori: Specialisti.<br>
	Descrizione: Permettere ad uno specialista di poter creare il proprio profilo, dunque di inserire una descrizione di lui e del suo lavoro, oltre che dei suoi orari di ricevimento e tariffe.

5) Calendario:<br>
	Attori: Utenti, Specialisti.<br>
	Descizione: Visualizzazione di un calendario e pop-up in caso di appuntamenti presi, sia per specialisti che per utenti, permettendo la cancellazione dell'appuntamento stesso in caso di imprevisiti.

6) Psicoeducazione:<br>
	Attori: Utenti.<br>
	Descrizione: Visualizza una sezione dedicata al perchè è importante la salute mentale, la descrizione sintetica dei disturbi e campanelli d'allarme più comuni.

7) Soccorso suicidi:<br>
	Attori: Utenti.<br>
	Descrizione: Tendina che permette di visualizzare una sezione dedicata al pronto soccorso in caso di tentato o pensieri suicidi, con numeri d'emergenza.

8) Leggere e scrivere recensioni su specialisti e sul sito in generale:<br>
	Attori: Utenti.<br>
	Descrizione: Sezione dedicata alle recensioni riguardo al sito ed alle varie esperienze con gli specialisti(si puo recensire uno specialista solo se si ha almeno fatto una seduta con lui).

9) Possibiliota per gli specialisti di leggere le recensioni sul sito di altri specialisti che lo utilizzano:<br>
	Attori: Specialisti.<br>
	Descrizione: Sezione dedicata alle recensioni lasciate da altri specialisiti, si può lasciare la propria recensione solo se si ha usato il sito per lavorare.

10) Sezione preferiti:<br>
	Attori: Utenti;<br>
	Descrizione: Menu dove si possono visualizzare gli specialisti "preferiti" e quelli con cui si è in cura per facilitare la ricerca agli utenti che vogliono ricercare il profilo di uno spacialista già noto 


## Requisiti non funzionali:

1) Rispetto norme gdbr: L'applicativo deve rispettare le norme europee GDBR in meriro al modo in cui le aziende e le altre organizzazioni trattano i dati personali.
	
2) Sicurezza: L'applicativo deve garanrire sicurezza su ogni aspetto.

## Use Case Diagram:
![diagramma UML](https://yuml.me/52f5e449.png)

## WBS:

1 Login e Registrazione:<br>
1.1 Login Utente<br>
1.2 Login Specialista<br>
1.3 Registrazione Utente<br>
1.4 Registrazione Specialista<br>

2 Introduzione(chi siamo noi sviluppatori):<br>
2.1 Introduzione Utenti<br>
2.2 Introduzione Specialisti<br>
2.3 Contatti e Social Media<br>

3 Ricerca Specialisti:<br>
3.1 Filtri di Ricerca<br>
3.2 Visualizzazione Risultati<br>

4 Creazione Profilo:<br>
4.1 Descrizione Personale<br>
4.2 Orari di Ricevimento<br>
4.3 Tariffe<br>

5 Calendario e Appuntamenti:<br>
5.1 Visualizzazione Calendario<br>
5.2 Prenotazione Appuntamenti<br>
5.3 Pop-up di Promemoria<br>
5.4 Cancella Appuntamento<br>

6 Psicoeducazione:<br>
6.1 Informazioni Salute Mentale<br>
6.2 Disturbi Comuni<br>
6.3 Campanelli d'Allarme<br>

7 Soccorso Suicidi:<br>
7.1 Informazioni di Emergenza<br>
7.2 Numeri d'Emergenza<br>

8 Recensioni:<br>
8.1 Scrivere Recensioni Utenti<br>
8.2 Leggere Recensioni Utenti<br>
8.3 Scrivere Recensioni Specialisti<br>
8.4 Leggere Recensioni Specialisti<br>

9 Sezione Preferiti:<br>
9.1 Aggiungi agli Specialisti Preferiti<br>
9.2 Visualizza Specialisti Preferiti<br>
9.3 Specialisti in Cura<br>

10 Requisiti Non Funzionali:<br>
10.1 Rispetto Norme GDPR<br>
10.2 Sicurezza Applicativa<br>
