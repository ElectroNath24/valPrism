## Installer SteelSeries GG
Pour commencer à utiliser ValPrism avec votre clavier, il vous faut installer le logiciel SteelSeries GG sur leur site officiel (https://fr.steelseries.com/gg).

## Configuration
Après avoir installé SteelSeries GG et connecté un clavier compatible, veuillez lancer ValPrism Link, puis cliquez sur le bouton "Link". L'appairage peut prendre plus ou moins de temps selon votre Wi-Fi. Une fois la tentative d'appairage effectuée, un message vous informera de la réponse, soit elle sera positive (réponse [200]) avec un message vous indiquant de pouvoir fermer la fenêtre, soit négative.<br>

![link](https://github.com/ElectroNath24/valPrism/assets/151563929/cb715654-1b09-46b8-b7c7-5433f5fe48f3)

Si la réponse est négative, veuillez vous référer à la page de [documentation](https://github.com/ElectroNath24/valPrism/blob/main/debugage/ValPrism%20Link.md)  dédiée et pour plus d'information sur le message d'erreur, voici une page  [wikipedia](https://fr.wikipedia.org/wiki/Liste_des_codes_HTTP)

## Configuration SteelSeries

Après avoir lancé une première fois ValPrism Link, allez sur le logiciel SteelSeries GG, veuillez vous rendre dans la rubrique "Engine", puis "Applis" et cherchez ValPrism.


![steelseries interface 1](https://github.com/ElectroNath24/valPrism/assets/151563929/1f27fcb3-30ef-4c90-b4d0-d6bba7ecce8e)

Cliquez sur "Configurer", puis vous entrerez dans l'interface ValPrism GameSense où vous pourrez configurer l'animation et l'attribution des touches.

![steelseries interface 2](https://github.com/ElectroNath24/valPrism/assets/151563929/7788eb3f-e41f-4551-b887-90f928983965)


En cliquant sur les touches du clavier dans l'application, vous pourrez y attribuer un "événement de jeu". Voici où les attribuer:
<p>
    - A : à mettre sur la touche "A".<br>
    - C : à mettre sur la touche "C".<br>
    - E : à mettre sur la touche "A".<br>
    - ANIMATION : à mettre sur les touches qui subiront une animation autre que A, C et E. Pour plus d'informations, rendez-vous au chapitre suivant.<br>
    - COMPTEURKILL :Renvoie 0% lorsqu'aucun kill n'a été effectué, 20% pour 1 kill, 40% pour 2, 60% pour 3, 80% pour 4 et 100% pour 5 (un ace).<br>
    - Aucun : à mettre sur les touches qui resteront par defaut.<br>
</p>

## Personnalisation de l'animation
### A,C et E

Dans l'interface ValPrism GameSense, cliquez d'abord sur "A", puis dans l'interface de gauche, choisissez la couleur au repos (0%) et la couleur activée (100%). Faites la même chose pour "C" et "E".

![steelseries interface 3](https://github.com/ElectroNath24/valPrism/assets/151563929/0b74b1c6-818d-4ba5-9100-175604ecea14)

P.S. : si vous souhaitez réutiliser une couleur récemment utilisée, vous pouvez cliquer sur les petits carrés situés sous le mélangeur.

### ANIMATION

L'événement "ANIMATION" est un événement qui aura une valeur qui va monter progressivement de 0% à 100% et redescendre à 0% plusieurs fois lorsque un ace sera effectué. Les paramètres que vous pouvez modifier sont :

1. Les effets :<br>
.  1. bicolore : la touche passera de la première couleur à la seconde.<br>
.  2. gamme de couleurs : vous allez choisir trois couleurs (ou plus) et la couleur passera de l'une à l'autre sans transition.<br>
.  3. monochrome : la couleur ne changera pas, mais ne sera pas celle par défaut.<br>
  
2.L'affichage sous forme de barre : peut être utilisé avec tous les effets, les touches s'allumeront les unes après les autres, représentant ainsi une barre de progression.




