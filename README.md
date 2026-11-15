# TD-Algorithme-exercices-trait-s-

exercice 1 : le test du rang ( pair ou impair)

Algorithme partie
Debut 
lire N
si N MOD 2 = 0 alors 
Afficher ("pair")
sinon
Afficher ("impair")
FinSi
Fin

exercice 2 : le plus grand de trois nombre 

Algorithme plus grand 
Debut 
lire A,B,C
si A>=B et A>=C alors 
Afficher (A)
sinon si B>=A et B>=C alors 
Afficher (B)
FinSi 
Fin


exercice 3 : table de multiplication 

Algorithme table multiplication 
Debut 
lire N
Pour i allant de 1 à 10 Faire 
Afficher (N,"X",i,"=",N*i)
FinPour 
Fin 


exercice 4: validation de l'entrainement 

Algorithme entraînement 
Debut 
lire N
jusqu'à N>0
S<-S+i
FinPour 
Afficher (S)
Fin


exercice 6: calcul de la factorielle 

Algorithme factorielle 
Debut 
lire N
F<-1
Pour i allant de 1 à N Faire 
F<-F*i
FinPour 
Afficher(F)
Fin 


exercice 8: triangle d'étoiles 

Algorithme triangle 
Debut 
lire H
Pour i allant de 1 à H Faire 
Pour j allant de 1 à i Faire 
FinPour 
Afficher ("")
FinPour 
Fin 


exercice 9: inverser les chiffres d'un nombre 

Algorithme inverse nombre 
Debut 
lire N 
Inverse de<-0
Tant que N>0 Faire 
R<-N MOD 10 
Inverse <- inverse*10+R
Fintant que
Afficher (inverse)
Fin

