# Visual-WSD

Proposta 1:
Creare una trasformazione dell'input di testo in un vettore in R^d (dove d è un hyperparameter) con un modello NLP e creare, per ogni immagine, un vettore in R^d con un modello 
di Computer Vision. 
Problema: Questi vettori sono effettivamente comparabili? Appartengono allo stesso feature space? E' possibile trovare un valore di d adatto ad espandere una porzione di testo
molto piccola e a comprimere immagina ad alta risoluzione?


Proposta 2:
Creare un vettore per il testo e un vettore per ogni immagine. 
Implementare una rete che prenda come input la concatenazione del vettore testo con il vettore di ognuna delle 10 immagini e che dia come output 1
se il vettore di testo e il vettore dell'immagine rappresentano lo stesso contenuto, 0 altrimenti.
In fase di testing, si sceglie l'immagine il cui logit è il più grande (tra le 10 immagini disponibili).


Proposta 3 (Advanced):
Fusion model
