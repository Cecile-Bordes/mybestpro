# Test Technique Mybestpro


## Les corrections


- **1- utf8 en utf-8**:
- **2- <html lang=fra en fr-FR**
- **3- type=text/javascript est déprécié**
- **4- font-family:Arial, manque le font-family:Arial;**
- **5- align:right;, manque le text-align:right;**
- **6- marign n'existe pas, margin si**
- **7- font-width:bold n'existe pas, font-weight:bold; si**
- **8- balises <b><a pas dans le bon sens <a href><b>**
- **9- balises <b> dépréciée, j'ai mis <strong>**
- **10- balises </br> mal écrite, <br /> est mieux fermé**
- **11- Manque le balisage <ul> autour des <li>**
- **12- id=bold, mis plusieurs fois, j'ai changé id en class et j'ai modifié dans le style .bold à la place de #bold**
- **13- ligne 82, erreur d'ordre de fermeture balises </p></ul>**
- **14- balise img, ajout de l'atribut alt**
- **15- Les attributs mis dans la balise table sont obsoletes. Je les ai supprimé et redéclaré dans le style**
- **16- Il manque la balise tr pour entourer la balise td colspan="2"**
- **17- 2 Erreurs font-style: underline, transformé en font-style: italic;text-decoration: underline;**
- **18- Manque la fermeture de la balise div id=page juste avant </body>**


## License

The MIT License (MIT)

Copyright (c) 2021 Cécile