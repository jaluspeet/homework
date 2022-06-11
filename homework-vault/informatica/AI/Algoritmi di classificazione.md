# Algoritmo KNN (K Nearest Neighbours)
Tutti gli algoritmi di classificazione generano output a partire da input elaborati da una funzione $$y=f(x)$$
L'output è già classificato e l'algoritmo trova la funzione 
![[../../zzzmedia/excalidrawings/Clustering 101937.excalidraw]]
## Bayes
$$P(A|B)=\frac{P(B|A) \cdot P(A)}{P(B)}$$
- A: probabilità che il messaggio sia spam
- B: probabilità che il messaggio contenga la parola congratulazioni
- B/A: probabilità che il messaggio contenga congratulazioni sapendo che è spam
- A/B: probabilità che il messaggio sia spam se contiene la parola congratulazioni

- principalmente utilizzato nei filtri *anti-spam*
- se il valore supera la soglia (stabilita dinamicamente) allora la mail viene classificata come spam
## Decision Tree
in pratica **Akinator**, esclude fino a giungere a un output con una soglia di certezza sufficientemente elevata

