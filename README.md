# DataMining2023
Progetto di Data Mining 2023: classificazione di P300 per speller da segnale EEG per cinque diversi pazienti.

Nel notebook "P300_data_exploration" i dati sono stati convertiti dal formato .mat al formato .json per una più facile lettura. 
Successivamente in "P300_ICA_preprocessing" i dati sono stati preprocessati mediante ICA. 
I cinque notebook "Model selection" contengono tutti i modelli che sono stati esplorati ed ottimizzati per ogni paziente. 
Nel notebook "Result unbalanced vs balnced data" sono stati messi a confronto gli score dei vari algoritmi per ogni paziente, individuando i modelli migliori. Questi sono stati infine raggruppati in un unico modello ensemble.
