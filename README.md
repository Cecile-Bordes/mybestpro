# Test Technique Mybestpro


## Les corrections

```javascript
- ** 1- utf8 en utf-8**:
- ** 2- <html lang=fra en fr-FR**
- ** 3- Modification de la balise shortcut qui doit être à la racine du projet et avoir une extension .ico
- ** 4- J'ai mis les styles de la page dans une feuille de style dans le dossier css
- ** 5- J'ai appelé le js en bas de page sur un serveur ou il est déjà hébergé en min.
- ** 6- type=text/javascript est déprécié**
- ** 7- font-family:Arial, manque le font-family:Arial;**
- ** 8- align:right;, manque le text-align:right;**
- ** 9- marign n'existe pas, margin si
- ** 10- font-width:bold n'existe pas, font-weight:bold; si
- ** 11- balises <b><a> pas dans le bon sens <a href><b>
- ** 12- balises <b> dépréciée, j'ai mis strong
- ** 13- balises </br> mal écrite, <br /> est mieux fermé
- ** 14- Manque le balisage <ul> autour des <li>
- ** 15- id=bold, mis plusieurs fois, j'ai changé id en class et j'ai modifié dans le style .bold à la place de #bold
- ** 16- ligne 82, erreur d'ordre de fermeture balises </p></ul>
- ** 17- balise img, ajout de l'atribut alt
- ** 18- Les attributs mis dans la balise table sont obsoletes. Je les ai supprimé et redéclaré dans le style
- ** 19- Il manque la balise tr pour entourer la balise td colspan="2"
- ** 20- Ajout au table des balises <thead> et <tbody>
- ** 20- 2 Erreurs font-style: underline, transformé en font-style: italic;text-decoration: underline;
- ** 21- Manque la fermeture de la balise div id=page juste avant </body>
- ** 22- J'ai ajouté une class .adresse à la fin de la page à la place du style en ligne.
```

## Pour une sémantique plus propre

```javascript
ajout des balises :
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
J'ai ajouté des balises HTML5 pour structurer la page <header>, <nav>, <main>, <footer>, <section>, <adresse>
J'ai ajouté des attributs role="" aria-label="" aux balises html5 pour une meilleure accessibilité
J'ai ajouté les 2 images dans un dossier img et je les ai trouvé sur https://www.wengo.fr/ en SVG.
```

## License

The MIT License (MIT)

Copyright (c) 2021 Cécile