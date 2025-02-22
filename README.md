# Separazione-di-immagini
Questo progetto ha l'obiettivo di separare un'immagine, ottenuta come somma di due immagini, nelle sue componenti originali.<br>
Le due immagini di origine, img1 e img2, provengono da dataset diversi: MNIST e Fashion-MNIST, rispettivamente.<br>
La rete neurale riceve in input l'immagine combinata (img1 + img2) e restituisce le predizioni (hat_img1 e hat_img2).<br>
Le prestazioni vengono valutate utilizzando l'errore quadratico medio (MSE) tra le immagini predette e quelle di riferimento.<br>
Entrambi i dataset (MNIST e Fashion-MNIST) sono in scala di grigi. Per semplicità, tutti i campioni vengono adattati alla risoluzione (32,32).<br>

Il progetto è stato realizzato nell'ambiente di sviluppo Google Colab.

Il progetto è stato realizzato da Francesco Maria Fuligni nell'ambito del corso di Introduzione all'Apprendimento Automatico, parte del Corso di Laurea in Informatica presso l'Università di Bologna, nell'anno 2025.
