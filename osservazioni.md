# Osservazioni — Esercitazione 0

Gruppo: C6

Componenti (nome, cognome e username GitHub di entrambi): Filippo Milozzi fmiloz, Aurora Marroni marroniaurora1304

URL del repository condiviso: https://github.com/marroniaurora1304/esercitazione-0-template

Chi ha usato la tastiera nello step 1 e nello step 2: entrambi

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: make (esegue compilazione con gcc allo standard C17)

Comando di esecuzione e risultato osservato: ./hello, nullo pre-modifica, stampa stringa: "Hello, computational physics!" post modifica, compilazione avvenuta con successo e output coerente con la richiesta

Che cosa ho capito su sorgente ed eseguibile: il sorgente è il file modificabile dove inserisco le istruzioni per il computer, l'eseguibile è un file binario che effettivamente compie i comandi del codice

Output richiesto e comportamento del programma prima della modifica: vedi sopra

Esito dopo la modifica e spiegazione della correzione: vedi sopra, ho inserito un printf nel codice (prima il codice era vuoto con solo il todo) 

## Step 1 — Git

Quali file ho incluso nel commit e perché: abbiamo fatto due commit, un primo dove abbiamo incluso solo il file osservazioni.md precedentemente modificato ed un secondo per il file sorgente hello.c. Perché sono gli unici su cui abbiamo lavorato apportando delle modifiche

Come ho verificato che la versione provata sia presente su GitHub: in testa alla pagina repo abbimao verificato la presenza dei due commit, aprendoli e controllandone il contenuto

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: prima del "git pull" il file locale non presentava la modifica fatta da remoto, mentre dopo il pull sul terminale è uscito un resoconto delle modifiche effettuate sul file. Non serve un nuovo clone perché voglio solo scaricare le modifiche fatte da remoto su GitHub.

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato:argomenti passati: ciao 12 3.5, comando eseguito: ./eco2 ciao 12 3.5, output: uguale agli argomenti

Che cosa posso concludere: tutto è andato bene, non è stato segnalato nessun errore ed il comando eco2 ha restituito 0 come previsto

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:argomenti passati: ciao dodici 3.5, comando eseguito: ./eco2 ciao dodici 3.5, output: Il secondo argomento deve essere un intero in base 10.

Che cosa ho capito su testo, conversioni e stampa: Ciò che scrivo dopo l'eseguive viene ricevuto tutto dal codice come stringa di testa, quindi il primo valore prima dello spazio viene preso così com'è sotto forma di testo, mentre gli altri elementi vengono convertiti dalle rispettive funzioni, se possibile, nel tipo corretto. In fase di stampa bisogna semplicemente usare %s %d %f in base al tipo di riferimento.

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: con argomenti validi non ci sono problemi, mentre con l'argomento dodici mi aspetto il messaggio di errore predefinito dalla funzione leggi intero in questo caso.

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati: in eco.txt per agomenti validi risulta la stringa di testo inserita in input, mentre per non validi risulta vuoto. Nel terminale con arg. validi nulla perchè ridirezionato la txt, non validi stampa mess. di errore impostato nella funzione di lettura. codici di uscita: 0 per arg validi, 2 altrimenti.

Come un controllo automatico può riconoscere un errore: utilizzzando i valori di return 0,2 (pass, fail)

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti: serve ricompilare ogni volta che viene cambiato il codice sorgente, mentre cambiare gli argomenti è solo per quando si vogliono testare input diversi
## Step 2 — Git

Come riconosco nella cronologia i commit dei due step: utilizzando git log

Come ho verificato che la versione finale sia presente su GitHub: su github da un altro dispositivo
