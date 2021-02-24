# Apps vs Web Apps

*  🔖 **Web optimisé mobile**
*  🔖 **Apports d'HTML 5**
*  🔖 **Single Page Application**
*  🔖 **Hybrides Apps**
*  🔖 **PhoneGap / Cordova**

___

## 📑 Web optimisé mobile

En dehors des solutions de développements natifs passée en revue dernièrement. Nous avons observé qu'avec HTML et les Web API il était possible d'accéder aux fonctionalitées du device.

Le langage dominant pour dynamiser un affichage est JavaScript, l'affichage HTML est stylisé en CSS.

![image](./resources/javascript.png)

En respectant les règles du `mobile first` il est possible d'orienter ses présentation pour la platefoem mobile et de ne pas être dépendant u'une solution visant uniquement une `plateforme`.

### 🏷️ **Environnement**

Chaque langage possède un `package manager`. C'est la base pour pouvoir utiliser votre programmation dans des environnements variés, importer des librairies, exécuter des commandes de compilation, lancer des test et bien d'autre. Le package manager de JavaScript est `npm`, distribuable avec la plateform logicielle Node.js.

> Vous avez un long chemin à parcourir pour identifier et utiliser ces outils.

[Node.js](https://nodejs.org/en/)

___


👨🏻‍💻 Manipulation

Installez Node Package Manager, discutons en.

___

## 📑 Single Page Application

JavaScript peut être utilisé comme langage d'appoint afin de fournir un effet graphique ou dynamiser une partie du document. Mais il est également possible de générer et dynamiser une ou plusieurs pages. Le concept de Single Page application utilise un seul fichier de présentation d'affichage au format html afin de le `dynamiser entièrement` et propsoser plusieurs pages sans jamais quiter ce fichier.

![image](./resources/spavsmpa.jpg)

C'est la technique utilisée pour produire des applications mobiles avec du code HTML/JavaScript

___

👨🏻‍💻 Manipulation

Identifiez des sites web que vous connaissez orientés SPA.

___

## 📑 Hybrides Apps

Avec le concept de `SPA` il est possible d'éxécuter son programe en dehors du cadre d'un navigateur web. C'est le concept d'applicaiton hybride. En utilisant un compilateur il est possible de transformer son code HTML/JavaScript en code spécifique à une plateforme.

![image](https://raw.githubusercontent.com/seeren-training/Ionic/master/wiki/resources/hybrid.jpg)

Le compilateur le plus courant s'appel `Cordova`.

[Cordova](https://cordova.apache.org/)

Ces applications sont en opposition des applications dites `natives`.

___

👨🏻‍💻 Manipulation

Quelles sont les différences majeures entre les applications `hybrides` et `natives`?

___

## 📑 PhoneGap / Cordova

Les applicaitons hybrides reposent donc sur le compilateur Cordova.

![image](https://raw.githubusercontent.com/seeren-training/Cordova/master/wiki/resources/cordova.png)

Si vous disposez des prérequis des plateformes ciblées, vous pouvez convertir votre programme dans le langage cible de la plateforme!

___

👨🏻‍💻 Manipulation

Installons cordova et créons un nouveau projet, observons ses spécificités.

___