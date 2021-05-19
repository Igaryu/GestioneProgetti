# GestioneProgetti - versione Linux con uso di contenitori VeraCrypt
## Gestione protetta progetti editoriali, e non solo.

 Il progetto ha lo scopo di proteggere, i nostri progetti editoriali in sviluppo. Esso è nato dalla necessità di proteggere un documento, durante la fase di stesura di un libro, volendo tenere occultato il contenuto del progetto, sino a competizione della stesura stessa.
 
 Chiaramente con lievi modifiche può essere adattato a qualsiasi documento che si voglia proteggere.
 
## I tools usati saranno:
  
 1. **bash** come ambiente di sviluppo ed esecuzione
 2. **GnuPG** per quanto riguarda la codifica dei documenti.
 3. **Contenitori .dmg** per le copie di backup (il progetto è stato originalmente sviluppato in ambiente MacOsx, ma prevede anche l'esecuzione in ambiente linux)
 4. **Contenitori VeraCrypt** per le copie in chiaro di backup ed eventuali copie in cloud.
 5. **bcwipe** e **wipe**, a seconda dell'ambiente di esecuzione, se MacOSX o GnuLinux. In caso di mancanza di questi software, verrà usato il normale comando *rm*, segnalando, all'utente, che non è stato possibile eseguire una cancellazione sicura dei dati.


###### Note:
 I nomi degli script iniziano con il prefisso **gpg** per rammentare che questo tool è il cuore del progetto. Esistono fondamentalmente due script da usare:

1. CreaProgetto
2. EditaProgetto

Il primo per creare il progetto e viene usato una volta sola per progetto, il secondo per aprire, editare, e chiudere, proteggendo nuovamente, il nostro progetto. 

I due script sono discussi più a fondo nel wiki che potete trovare [a questo link](https://gitlab.com/joseph.curto/GestioneProgetti/-/wikis/home).

***

Ultimo aggiornamento di questo documento: 27/03/2021

8E2C DB21 A55C A162 29C9  5FDE 69E9 C8DC FA4E 019C
