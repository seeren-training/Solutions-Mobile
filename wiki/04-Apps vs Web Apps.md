# Apps vs Web Apps

*  🔖 **Web optimisé mobile**
*  🔖 **Apports d'HTML 5**
*  🔖 **Single Page Application**
*  🔖 **Hybrides Apps**
*  🔖 **PhoneGap / Cordova**

___

## 📑 Web optimisé mobile

En dehors des solutions de développements natifs passée en revue dernièrement. Nous avons observé qu'avec HTML et les Web API il était possible d'accéder aux fonctionnalités du device.

Le langage dominant pour dynamiser un affichage est JavaScript, l'affichage HTML est stylisé en CSS.

![image](https://raw.githubusercontent.com/seeren-training/Solutions-Mobile/master/wiki/resources/javascript.png)

En respectant les règles du `mobile first` il est possible d'orienter ses présentation pour la plateforme mobile et de ne pas être dépendant u'une solution visant uniquement une `plateforme`.

### 🏷️ **Environnement**

Chaque langage possède un `package manager`. C'est la base pour pouvoir utiliser votre programmation dans des environnements variés, importer des librairies, exécuter des commandes de compilation, lancer des test et bien d'autre. Le package manager de JavaScript est `npm`, distribuable avec la plateforme logicielle Node.js.

> Vous avez un long chemin à parcourir pour identifier et utiliser ces outils.

[Node.js](https://nodejs.org/en/)

___

👨🏻‍💻 Manipulation

Installez Node Package Manager, discutons en.

___

### 🏷️ **Exécution**

Pour pouvoir exécuter la boucle d'interprétation:

```bash
node
```

Pour installer un package disponible sur npm:

```bash
npm install @angular/cli
```

[Npm](https://www.npmjs.com/)

Pour pouvoir exécuter un binary d'un package installé:

```bash
npx ng
```

___

## 📑 Single Page Application

JavaScript peut être utilisé comme langage d'appoint afin de fournir un effet graphique ou dynamiser une partie du document. Mais il est également possible de générer et dynamiser une ou plusieurs pages. Le concept de Single Page application utilise un seul fichier de présentation d'affichage au format html afin de le `dynamiser entièrement` et proposer plusieurs pages sans jamais quitter ce fichier.

![image](https://raw.githubusercontent.com/seeren-training/Solutions-Mobile/master/wiki/resources/spavsmpa.jpg)

C'est la technique utilisée pour produire des applications mobiles avec du code HTML/JavaScript

___

👨🏻‍💻 Manipulation

Identifiez des sites web que vous connaissez orientés SPA.

___

## 📑 Hybrides Apps

Avec le concept de `SPA` il est possible d’exécuter son programme en dehors du cadre d'un navigateur web. C'est le concept d’application hybride. En utilisant un compilateur il est possible de transformer son code HTML/JavaScript en code spécifique à une plateforme.

![image](https://raw.githubusercontent.com/seeren-training/Ionic/master/wiki/resources/hybrid.jpg)

Le compilateur le plus courant s'appelle `Cordova`.

[Cordova](https://cordova.apache.org/)

Ces applications sont en opposition des applications dites `natives`.

___

👨🏻‍💻 Manipulation

Quelles sont les différences majeures entre les applications `hybrides` et `natives`?

___

## 📑 PhoneGap / Cordova

Les applications hybrides reposent donc sur le compilateur Cordova.

![image](https://raw.githubusercontent.com/seeren-training/Cordova/master/wiki/resources/cordova.png)

Si vous disposez des prérequis des plateformes ciblées, vous pouvez convertir votre programme dans le langage cible de la plateforme!

___

👨🏻‍💻 Manipulation

Installons cordova et relevons les lignes de commandes principales

___

Une fois les commandes principales ade cordova découvertes vous pouvez facilement créer un projet, ajouter une plateform et tenter un build sur un device connecté à condition que les pré requis soient présents!

* Mode développeur
* Java en variable d'environnement
* Android Studio, Graddle, SKD plateform, SDK build tools
* Graddle en variable d'environnement

___

👨🏻‍💻 Manipulation

Allez dans la direction du build hybride en tentant de déployer l'application crée sur votre device. Des erreurs? Pas de problème nous prendrons le temps de les régler sur le module concerné mais vous avez un problème en cours!