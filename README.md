# ligne du programme 
la premiere ligne du programme **#inlude <stdio.h>** est une commande des prépocesseur, qui indique à un compilateur C d'inclure les hichier stdio.h avant de passer à la complitation proprement dite.

la ligne suivante **int main()** est une fonction principale ou l'execution du programme commence.

la ligne suivante __/**</__ sera ignorée par le complilateur et est placée pour ajouter des commentaire supplementaire dans des programme


la ligne suivante *prinf(..)* est une autre fonction disponible en C qui provoque le message" Hello Word" à afficher sur l'écran

la ligne suivante *renvoie 0*; termine la finction **main()** et renvoit la valeur de 0.

## Compliler et exécuter le programme C

Les étapes de la complitaion sont :

Dans le terminal je tape la commande **gcc HelloWord.C**

Il est obligatoire dans *C* que chaque terminateur d'instruiction.Autrement dit;chaque instruction individuelle doit se terminer par un point-virgule *;*. En Bref il indique la fin d'une entité logiqie .


```printf("Hello, World! \n");
    return 0;
```
 *C* est un langage de  programmation sensible à  la case Il prend Majuscule pour Majuscule et Muniscule pour Muniscule:
 ex: Annette est different de annette

 L'indentifiant Ac est un nom utilisé pour identifier une variable, une fonction ou tout autre élément défini par l'utilisateur. 
 de soulignement et chiffres (0à9).

Un Identificateur Commence par une lettre \*[A-Z,a-z]* ou un trait de soulignement *"_"* ou plusieurs lettres, traits
 Par contre *C* N'autprise pas les caracteres de ponctuation telque @,$ et %, 


Liste des mots réserver en C

<table>
    <tr>
        <th>auto<th>
        <th>Break<th>
        <th>case<th>
    <tr>
<table>

|Auto|break|case| auto	|else|long|switch|case|extern|return|union|enum|register|	typedef|case|extern	return	union|
<!-- | ---|---|---|---| -->
| auto	|else|long|switch|
<!-- |---|---|--- |---| -->
|case|extern|return|union|
<!-- | ---|---|---|---|---|---| -->
|enum|register|	typedef|
<!-- | ---  |---|---|---|---|---| -->
|case|extern	return	union
<!-- | ---  |---|---|---|---|---| -->
|char	|float	short	unsigned
<!-- | ---  |---|---|---|---|---| -->
|const	|for	signed	void
<!-- | ---|---|---|---|---|---| -->
|continue|goto|sizeofvolatile|
<!-- | ---  |---|---|---|---|---| -->
|default|if	|static	|while|
<!-- | ---  |---|---|---|---|---| -->
|do	int	|struct	_Packed|
<!-- | ---  |---|---|---|---|---| -->
|double |break|

### Espace Blanc en c

une ligne ne contenant que des espaces blancs; éventuellement avec un commentaire, est connue comme une ligne vide ,et un complilateur *C* L'ignore totalement"

Les espaces Blancs sont les terme utilisé en C pour décrire les blancs, les tabulations;les caractères de saut de ligne et les commentaires.les espaces Blanc séparent une paryie d'une instruction d'une autre et permettent au complilateur d'indentifier ou un élement dans une instruction , comme int, se termine et l'élement suivant commence .Par Conséquent, Dans l'énonc" suivant-

```int age;
```
il doit y avoir au moins un caractère d'espacelent(généralement un espace) entre int et age pour que le complilateur puisse les distinguer .D'autre part;Dans l"énoncé suivant:

```fruit = apples + oranges; //get the total fuit
```

aucun caractère d'espacement n'est nécessaire entre fruit et =, ou entre = et pommes, bien que vous soyez libre d'en inclure si vous souhaitez augmenter la lisibilité.


## Types de données

Ls types de données en c font réference à un système étendu utiisé pour déclarer des variables ou des fonctions de differents types.le type d"une variable détermine l'espace qu"elle occupe dans le stockage et la façon dont le modèle stocké est intérpreté.



En c Les types en c Peuvent être clasées comme suit:

