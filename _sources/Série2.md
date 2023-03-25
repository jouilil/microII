### Série 2 : CPP

<i>Conçue et développée par l'Equipe de Micro 2. </i>

<i> Mercredi 29 Mars 2023</i>


###### Exercice 1

```{admonition} Enoncé de l'exercice 1
Une industrie qui évolue dans un contexte de concurrence pure et parfaire est composée de 120 entreprises. Chacune de ces entreprises a une fonction de coût total donnée par l'équation suivante : 

$$
CT(Q) = 2Q^2+4Q+162
$$

La demande du marché s’écrit :  

$$
P=-\dfrac{1}{15}Q + 442
$$


1. Déterminer l'offre individuelle. 

2. Déterminer l'offre globale du marché. 

3. Calculer le prix et la quantité d'équilibre du marché. 

4. Déterminer l'équilibre de la firme à court terme. Calculer son profit. 


```


```{admonition} <font color='blue'>Réponse de l'exercice 1</font>
:class: attention, dropdown

1. Déterminer l'offre individuelle. 

$$
P= Cm  & \Rightarrow  P = \dfrac{dCT(Q)}{dQ} \\
              & \Rightarrow P = 4Q+4 \\
              & \Rightarrow Q(P) = 0.25P-1  ~~\text{Si}~~ P \geq SR\\
$$

$$
SR= Min ~~ CTM = Min ~~ \dfrac{CT}{Q}= Min ~~ 2Q+4+\dfrac{162}{Q}
$$

$$
CTM'=0 & \Rightarrow  2 - \dfrac{162}{Q^2}=0 \\
              & \Rightarrow Q^2 = 81 \\
              & \Rightarrow Q = 9
$$

Donc :

$$
SR = Min ~~ CTM = CTM(9) = 2\times9 + 4 +\dfrac{162}{9} = 40
$$

Ainsi, l'offre individuelle est donnée par l'expression suivante :



$$
Q(P) = 
\left\{
    \begin{array}{ll}
    0.25P-1  ~~\text{Si}~~ P \geq 40\\ 
    0 ~~~~~~~~~~~~~~~~~ \text{Sinon}
    \end{array}
\right.
$$

2- Offre globale du marché

$$
O^G = \sum_{i=1}^{120} Q_i(P) = 120 (0.25P-1)= 30P-120
$$

3- Calculer le prix et la quantité d'équilibre du marché. 

$$
P=-\dfrac{1}{15}Q+442  & \Rightarrow P-442=-\dfrac{1}{15}Q\\
              & \Rightarrow Q(P)=6630-15P
$$

$$
Q=6630-15P = 30P-120  \Rightarrow 6750= 45P  \Rightarrow P = 150
$$

Pour P= 150 :

$$
Q = 6630-15 \times 150   \Rightarrow  Q = 4380
$$


4- Déterminer l'équilibre de la firme à court terme. Calculer son profit. 



$$
Cm= P
$$

$$
Q(P) = 0.25P-1 ~~si ~~ P \geq 40
$$

Pour $P =150$, on a  $Q = 36,5$ et $\pi= 150\times36,5-CT(36,5)$

```

###### Exercice 2

```{admonition} Enoncé de l'exercice 2

Sur un marché de CPP composé de 50 firmes qui ont une structure de coût identique telle que :

$$
CT=5 Q^2+30Q+125
$$
     
La fonction inverse de la demande s’écrit : 

$$
P=-0,1Q+1500
$$

1. Déterminer le prix d’équilibre de courte période, la quantité échangée à ce prix et l’offre de chaque firme.

2. Déterminer le profit de la firme représentative.

3. Ce profit peut-il durer à long terme ?
```


```{admonition} <font color='blue'>Réponse de l'exercice 2</font>
:class: attention, dropdown

1. Déterminer le prix d’équilibre de courte période, la quantité échangée à ce prix et l’offre de chaque firme.

$$
P= Cm  & \Rightarrow  P = \dfrac{dCT(Q)}{dQ} \\
              & \Rightarrow P = 10Q+30 \\
              & \Rightarrow Q(P) = 0.1P-3  ~~\text{Si}~~ P \geq Min ~~ CTM\\
$$

$$
SR= Min ~~ CTM = Min ~~ \dfrac{CT}{Q}= Min ~~ 5Q+30+\dfrac{125}{Q}
$$

$$
CTM'=0 \Rightarrow  Q^2 = 25  \Rightarrow Q = 5
$$

Donc :

$$
Min ~~ CTM = CTM(5) = 80
$$

Offre globale 

$$
O^G= 15000-10P
$$

Offre = Demande

$$
5P-150 = 15000-10P 
$$

Ainsi P =1010 et $Q_G$ = 4900

L'offre individuelle est donnée par :

$$
Q_i = \dfrac{Q_G}{N}= \dfrac{4900}{50}= 98
$$

2- Déterminer le profit de la firme représentative.

$$
\pi = RT-CT= pQ-CT = 47895
$$

3- Ce profit peut-il durer à long terme ?

Le profit réalisé par les entreprises est important. Ce profit important attire de nouvelles entreprises ( car l'acces au marché en CPP est libre). Ainsi, l'offre globale va uagmenter. Si la demande reste inchangée, il en resultera une baisse du prix d'équilibre et du profit de chaque entreprise (jusqu'à $\pi=0$).

Ainsi, en longue période :

$$
P=Cm= CM
$$

$$
Q= 5 ~~ et ~~ P=80 \Rightarrow  \pi = 0
$$

```


###### Exercice 3


```{admonition} Enoncé de l'exercice 3

Supposons que sur le marché des bananes dans une région donnée, les quantités demandées varient de la façon suivante en fonction du prix :

$$
Q^D= -40P + 4100
$$

Par ailleurs, les quantités offertes varient en fonction du prix :

$$
Q^O= 20P - 100
$$

1. Déterminer le prix d'équilibre et la quantité échangée à ce prix.

2. Sur ce marché, on recense 200 firmes de même dimension et possédant les mêmes coûts. Prenons l'une de ces entreprises, l'entreprise A par exemple. Son coût total en fonction de la quantité produite est de :

$$
CT(Q)= 5Q^2 + 5Q + 100
$$

2.1. Pour quel volume de production, son profit sera-t-il maximum ?

2.2. Montrer que ce volume est bien le (1/200)ème du volume vendu dans la branche.

3. L'entrée dans la branche est libre.

3.1. Déterminer le prix d'équilibre à LT et la quantité échangée dans la branche.

3.2. Déterminer la quantité qui serait vendue par la firme A et son profit à LT.

```


```{admonition} <font color='blue'>Réponse de l'exercice 3</font>
:class: attention, dropdown

Supposons que sur le marché des bananes dans une région donnée, les quantités demandées varient de la façon suivante en fonction du prix :

$$
Q^D= -40P + 4100
$$

Par ailleurs, les quantités offertes varient en fonction du prix :

$$
Q^O= 20P - 100
$$

1- Déterminer le prix d'équilibre et la quantité échangée à ce prix.

Prix et quantité d’équilibre 

A l’équilibre : 

$$
Q^D = Q^O  & \Rightarrow  -40P + 4100 = 20P – 100 \\
                & \Rightarrow P = 70
$$

$$
Q^O = 20(70) – 100 = 1300
$$

$$
Q^D = -40(70) + 4100 = 1300
$$

$$
Q = 1300
$$

2- Sur ce marché, on recense 200 firmes de même dimension et possédant les mêmes coûts. Prenons l'une de ces entreprises, l'entreprise A par exemple. Son coût total en fonction de la quantité produite est de :

$$
CT(Q)= 5Q^2 + 5Q + 100
$$

2.1. Pour quel volume de production, son profit sera-t-il maximum ?


$\pi$ est maximum si P = Cm

$$
70 = 10Q + 5 \Rightarrow Q = 6,5
$$

2.2. Montrer que ce volume est bien le (1/200)ème du volume vendu dans la branche.

On sait que le volume vendu dans la branche est 1300 (Offre = Demande) Et que pour une entreprise le volume vendu est $Q_i = 6,5$.

Pour 200 entreprises le volume vendu est $6,5 \times 200 = 1300$ Donc, 6,5 est le 1/200ème du volume vendu dans la branche



3- L'entrée dans la branche est libre.

3.1. Déterminer le prix d'équilibre à LT et la quantité échangée dans la branche.

$$
CT(Q) = 5Q^2 + 5Q + 100  \Rightarrow CTM = 5Q + 5 + 100/Q 
$$
 CTM est minimum implique que :
 
$$
CTM'(Q) = 0 & \Rightarrow 5 – 100/Q^2 = 0 \\
               & \Rightarrow Q_i ≈ 4,5 
$$

$CTM = 5(4,5) + 5 + 100/4,5$

$P = CTM ≈ 50$

La quantité échangée au niveau de la branche :

$Q^{LT} = - 40 P^{LT} + 4100 = - 40(50) + 4100$

$Q^{LT} = 2100$



3.2. Déterminer la quantité qui serait vendue par la firme A et son profit à LT.

$Q^{LT}_i = [20(50) – 100]/200$

$Q^{LT}_i = 4,5$

$\pi^{LT}_i = RT – CT = P \times Q – (CM \times q) = (4,5 \times 50) – (50 \times 4,5)$

$\pi^{LT}_i = 0$



```

###### Exercice 4

```{admonition} Enoncé de l'exercice 4

Soit un marché de CPP ; considérons les fonctions de demande et d'offre suivantes:

$$
Q^D = -2P + 10 ~~~~~~~;~~~~~~~~~
Q^O = P + 4
$$

1. Déterminer le prix et la quantité d'équilibre

2. Supposons que l'offre se déplace, soit $Q^O= P + 1$, la demande inchangée. Quels sont les nouveaux prix et la quantité d’équilibre.

3. Avec le déplacement de l'offre, si le prix reste inchangé, ce marché serait en déséquilibre. Calculer le manque provisoire qui en découle.



```


```{admonition} <font color='blue'>Réponse de l'exercice 4</font>
:class: attention, dropdown

1. Déterminer le prix et la quantité d'équilibre

$$
Q^D = Q^O  & \Rightarrow -2P + 10 = P + 4 \\
            & \Rightarrow -3P =-6 \\
            & \Rightarrow P =2
$$

$$
Q^{eq}= -2\times 2 + 10 = 6
$$

Au prix de 2 dhs, la quantité d’équilibre est de 6 unités

2- Supposons que l'offre se déplace, soit $QO = P + 1$, la demande inchangée. Quels sont les nouveaux prix et la quantité d’équilibre.

$$
Q^D = Q^O  & \Rightarrow -2P + 10 = P + 1 \\
            & \Rightarrow -3P =- 9\\
            & \Rightarrow P =3
$$

$$
Q^{eq}= -2\times 3 + 10 = 4
$$

Au prix de 3 dhs la quantité d’équilibre est de 4 unités.

3- Avec le déplacement de l'offre, si le prix reste inchangé, ce marché serait en déséquilibre. Calculer le manque provisoire qui en découle.

Nous avons : $Q^O = P + 1$ et $P = 2$

$$
Q^O = 3
$$

$$
Q^D = -2P + 10 = -2(2) + 10 \Rightarrow Q^D = 6
$$

Ainsi, le marché est en déséquilibre, le manque provisoire est de 3 unités. 


```

###### Exercice 5


```{admonition} Enoncé de l'exercice 5

Cinquante entreprises concourent à la production de bicyclettes et leurs fonctions de coûts sont identiques :

$$
CT(Q)= 0,2Q^2 + 10Q + 20
$$

La demande de bicyclettes est donnée par la fonction :

$$
Q^D= 100P + 3250
$$

1. Déterminer l’équation de l’offre de chaque entreprise et celle de l’offre globale

2. Calculer le prix d'équilibre

3. Le gouvernement décide de taxer les bicyclettes de 9dh par unité produite et vendue :

3.1. Quel sera le nouveau prix d'équilibre ?

3.2. Calculer 1a quantité vendue par la branche et par chaque entreprise

```



```{admonition} <font color='blue'>Réponse de l'exercice 5</font>
:class: attention, dropdown

1. Déterminer l’équation de l’offre de chaque entreprise et celle de l’offre globale

Pour chaque entreprise, la condition de maximisation du profit se traduit par :

$$
P = Cm & \Rightarrow P = 0,4qi + 10 \\
        & \Rightarrow qi = 2,5P – 25 ~~~~\text{(c’est l’offre de l’entreprise i)}
$$

L’offre globale 

$$

Q^O = 50 𝑞𝑖= 50qi = 50(2,5P – 25) \Rightarrow  Q^O = 125P – 1250
$$

2- Calculer le prix d'équilibre

$$

Q^O = Q^D & \Rightarrow  125P – 1250 = -100P + 3250 \\
        & \Rightarrow P = 20
$$

$$
Q^O = 125(20) – 1250 = 1250
$$


3- Le gouvernement décide de taxer les bicyclettes de 9dh par unité produite et vendue :

3.1. Quel sera le nouveau prix d'équilibre ?

L’équilibre après la taxe :

Le nouveau prix d’équilibre :

$$
Q^O = 125P – 1250 \Rightarrow P = 0,008Q^O + 10
$$

En ajoutant la taxe de 9dhs, la dernière équation devient :

$P = 0,008Q^O + 19$ [c’est la fonction de l’offre globale]

3.2. Calculer 1a quantité vendue par la branche et par chaque entreprise


La quantité vendue par la branche et par chaque entreprise

Le nouveau prix d’équilibre est tel que : $Q^O = Q^D$

Nous avons  :

$$
Q^D = -100P + 3250 \Rightarrow  P = -Q^D/100 + 32,5
$$

Et nous avons trouvé que $ P = 0,008Q^O + 19$

Avec $QO = QD = Q$, nous aurons : 

$$
0,008Q + 19 = -Q/100 + 32,5 \Rightarrow Q = 750 ~~ \text{[quantité vendue par la branche]}
$$ 

$$
P = 0,008(750) + 19 \Rightarrow P = 25 
$$

La production de chaque entreprise est :

$$
qi = 750/50 \Rightarrow qi = 15
$$



```


```

```

<center><i> Bon courage  à vous tous !</i></center>

