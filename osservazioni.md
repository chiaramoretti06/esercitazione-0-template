# Osservazioni — Esercitazione 0

Gruppo:

Componenti
(Chiara Moretti, chiaramoretti06
Jacopo Maggiore, maggiorejacopo):

URL del repository condiviso:https://github.com/chiaramoretti06/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2: Entrambi alternandoci 

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione:gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato:./hello 
prima della modifica: il rpogramma complica ed esegue , ma non stampa nulla;, sul terminale ricompare subito il prompt.
dopo la modifica: il programma stampa "hello, computational physics" seguito da un a capo. Il ./ serve a indicare alla shell che il rpogramma si trova nella cartella corrente. 

Che cosa ho capito su sorgente ed eseguibile:hello.c e' il sorgente (file di testo in linguaggio c), hello e' l'eseguibile (file binario in linguaggio macchina prodotto dal compilatore e per questo non e' necessario in quanto rigenerabile aggiungerlo al commit).

Output richiesto e comportamento del programma prima della modifica:
Output richiesto: Hello, computational physics! seguita da un a capo (\n)
Prima della modifica: il template di hello.c conteneva un TODO al posto dell'istruzione di stampa, quindi il programma era corretto, ma non stampava nulla. 


Esito dopo la modifica e spiegazione della correzione:
Abbiamo sostituito il TODO con l'istruzione
printf("Hello, computational physics!\n");
Dopo la compilazione non sono comparsi warning e ./hello stampa quanto richiesto. 

## Step 1 — Git

Quali file ho incluso nel commit e perché:
Abbiamo incluso solo hello.c e osservazioni.md perche' l'eseguibile (hello) puo' essere rigenerato a partire dal file sorgente (hello.c). 

Come ho verificato che la versione provata sia presente su GitHub:con git log --oneline abbiamo letto l'identificativo dell'ultimo commit locale. Su GitHub,  nella pagina dei repository abbiamo aperto la cronologia dei commit e controllato che ;l'ultimo avesse lo stesso identificativo e messaggio. Abbiamo aperto aperto hello.c su GitHub e controllato contenesse il printf corretto. Per ultimo, abbiamo fatto git status per vedere se ci fossero commit locali non ancora inviati. 

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone:aprendo osservazioni.md sul computer la frase non c'era, il commit presente su github era solo su repository remoto. Con git pull abbiamo scaricato i nuovi commit e ora aprendo il file le modifiche c'erano. Git clone non serviva perche' crea da zero una nuova copia di repository e sarebbe inutile, a noi basta aggiungere le modifiche apportate su github.

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato:

Che cosa posso concludere:

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:

Come un controllo automatico può riconoscere un errore:

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:

## Domande di stimolo
