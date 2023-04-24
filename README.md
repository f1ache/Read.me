# Attributi


![Language](https://img.shields.io/badge/Spellcheck-Pass-green?style=flat) |Indica che lo spelling sia del README.md che della documentazione è corretto (verifica errori di battitura)
![Platform](https://img.shields.io/badge/OS%20platform%20supported-Windows-blue?style=flat)|Piattaforma OS su cui è eseguito il programma
![Language](https://img.shields.io/badge/Language-Python-yellowgreen?style=flat) |Linguaggio utilizzato
![Testing](https://img.shields.io/badge/PEP8%20CheckOnline-Passing-green)|verifica correttezza secondo lo standard PEP8 o simili

## Descrizione

Il mio programma Python  esegue alcune operazioni sui file presenti nella directory corrente e nelle sue sotto-directory. In particolare, il programma stampa alcune informazioni sulle proprietà dei file, come i permessi di accesso in formato ottale e la versione alfabetica in stile Linux.Il codice è suddiviso in tre parti principali: l'importazione di una libreria, la definizione di una funzione e il codice principale.Nella prima parte, viene importata la libreria os. Questa libreria fornisce una serie di funzioni per interagire con il sistema operativo, ad esempio per accedere alle informazioni sui file.Nella seconda parte, viene definita una funzione chiamata bin_linux, che prende in input una stringa binaria rappresentante i permessi di accesso di un file e restituisce la loro versione alfabetica in stile Linux. La funzione utilizza un ciclo for per iterare attraverso la stringa binaria a gruppi di tre bit.
Per ogni gruppo, viene utilizzata una serie di istruzioni if/elif per determinare il corrispondente permesso di accesso nella versione alfabetica in Linux. Infine, i permessi di accesso sono concatenati in una stringa e restituiti come risultato. Nella terza parte, il codice principale utilizza la funzione os.walk() per iterare attraverso i file presenti nella directory corrente e nelle sue sotto-directory. Per ogni file, vengono stampate alcune informazioni, come il nome del file, le sue proprietà, il valore della proprietà st_mode in formato ottale e in versione alfabetica in stile Linux.
In sintesi, il programma esegue una scansione dei file nella directory corrente e nelle sue sotto-directory, e stampa alcune informazioni sulle proprietà dei file, tra cui i permessi di accesso in formato ottale e in versione alfabetica in stile Linux.
[Il output del file ](https://github.com/f1ache/Read.me/blob/main/Capture.JPG)

## Requisiti

1)Python 3.x installato sul sistema.
2)Conoscenza di base della sintassi Python e di come utilizzare il modulo "os".
3)Conoscenza di utilizare il ambiente virtuale Python


## Esecuzione

Per eseguire questo codice Python, segui questi passaggi:
1.Apri una finestra di Commmand Promt o un ambiente virtuale python 
2.Naviga nella directory in cui hai salvato il file Python utilizzando il comando cd 
3.Esegui il file Python con il comando attributi.py per [Esempio ](https://github.com/f1ache/Read.me/blob/main/Capture1.JPG)

## Tags

File system
Permessi di accesso
Ambiente virtuale python
Proprietà del file
Os module
Ffblk
Funzion
Codifica

## Author

Gabriel coropat
