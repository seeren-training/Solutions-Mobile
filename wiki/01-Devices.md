# Devices

*  🔖 **Évolution des écrans et devices**
*  🔖 **Le marché du mobile**
*  🔖 **Du Wap à HTLM 5**
*  🔖 **Responsive Design**

___

## 📑 Évolution des écrans et devices

Il faut attendre 2002 pour voir arriver les couleurs sur l'écran des terminaux et c'est en 2009 que le premier modèle avec écran `AMOLED` arrive sur le marché.

![image](https://raw.githubusercontent.com/seeren-training/Solutions-Mobile/master/wiki/resources/evolution-ecran-samsung.jpg)

> Les développeurs doivent trouver des solutions d'ergonomie pour supporter des affichages aux tailles et proportions variées.

Les écrans gagnent en surface et trouvent des solutions pour rester portables

___

👨🏻‍💻 Manipulation

Essayez de relevez des innovations actuelles concernant les formats d'écrans afin d'en déduire des adaptations à prendre en compte.

___

## 📑 Le marché du mobile

Le marché divisé par deux constructeur dominant s'ouvre avec de nouveaux arrivants.

![image](https://raw.githubusercontent.com/seeren-training/Solutions-Mobile/master/wiki/resources/constructeurs.png)

### 🏷️ **Livraison**

Avec une apogée en 2016 le nombre de livraison s'est stabilisé avec une valeur minimal assurée par le renouvellement.

![image](https://raw.githubusercontent.com/seeren-training/Solutions-Mobile/master/wiki/resources/livraison.png)

L'on peut observer avec le cumul des livraison, la stabilisation et le léger déclin des opportunités du marché.

![image](https://raw.githubusercontent.com/seeren-training/Solutions-Mobile/master/wiki/resources/livraison-decenie.png)

___

## 📑 Du Wap à HTML 5

Le protocol de communication à évolué en fonction de la capacité des devices.

### 🏷️ **Wap**

> Le protocole Wireless Application Protocol est un protocole apparu en France en 1999 qui permettait d'accéder à Internet à partir d'un appareil de transmission sans fil.

Il redéfinit le protocole HTTP, le format de présentation HTML et l'interactivité obtenue par le langage JavaScript pour les adapter au monde des périphériques ayant un écran de taille réduite, un processeur de faible puissance et une autonomie limitée (téléphones mobiles).

Les services WAP ont perdu de leur attrait depuis l’avènement des smartphones, équipés de processeurs puissants, d'écrans de taille suffisante, disposant de débits élevés et capables d'interpréter nativement le HTML et le JavaScript. 

### 🏷️ **HTML 5**

La version 5 propose de standardiser les `web API`.

[Spécifications](https://developer.mozilla.org/fr/docs/Web/API#sp%C3%A9cifications)

Il est alors possible avec du développement web d'accéder aux fonctionnalités du device parce qu'interprété comme application web.

![image](https://raw.githubusercontent.com/seeren-training/Solutions-Mobile/master/wiki/resources/html5-features.jpg)

___

👨🏻‍💻 Manipulation

Après avoir observé la spécification, relevez des `web API` dont vous trouvez un impact directe sur les applications que vous utilisez.

___

## 📑 Responsive Design

Le HTML5 permet d'accéder aux fonctionnalités du device mais offre des solutions d'affichage pour résoudre le problème de la diversité des formats.

[Media queries](https://developer.mozilla.org/fr/docs/Web/CSS/Requ%C3%AAtes_m%C3%A9dia/Utiliser_les_Media_queries#combiner_plusieurs_types_ou_caract%C3%A9ristiques)

### 🏷️ **Mobile First**

> Il est possible avec la `At Rule` "Media" de spécifier des règles d'affichage en fonction d'un type de support et de contraintes données. 

Un design responsive correspond à utiliser des unités `relatives` et de s'`adapter` aux différents formats possibles.

![image](https://raw.githubusercontent.com/seeren-training/Solutions-Mobile/master/wiki/resources/mobile-first.png)

La règle du mobile first correspond à cibler en base de développement les écrans mobile et à enrichir ses règles stylistiques en fonction d'une capacité d'affichage qui augmente.

### 🏷️ **Breakpoints**

L'adaptabilité se définir en fonction de points de ruptures. Observons les points de ruptures admis.

[Bootstrap Breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/)

|Breakpoint|Terminologie|Dimensions|
|--|--|--|
|X-Small|None|<576px|
|Small|sm|≥576px|
|Medium|md|≥768px|
|Large|lg|≥992px|
|Extra large|xl|≥1200px|
|Extra extra large|xxl|≥1400px|

___

👨🏻‍💻 Manipulation

Observons des applicaitions web ou mobile qui utilise ce principe. Et au fait, pourquoi du mobile first et pas l'inverse?