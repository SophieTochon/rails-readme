# Hello !

**On va parler Rails tou.te.s les deux ❤️ _Prêt.e ?_**

La consigne donnée par THP est de détailler certains points particuliers, lesquels sont :

1. La différence entre un site statique et un site dynamique
2. Le MVC
3. Les routes
4. Les bases de données
5. GET / POST
6. Le concept de migration
7. Les relations entre les modèles et les BDD
8. Les fonctions du CRUD

**Mais avant !** J'aimerais qu'on prenne quelques profondes respirations pour détendre un peu son corps et son esprit, et aborder Rails bien tranqillement.

<p> <img "http://www.storystandardsguide.com/wp-content/uploads/2018/01/Yoga.jpeg"/> </p>
*Si t'es chaud.e, tu peux aussi aller faire la posture du guerrier sur une petite plage au coucher du soleil.*

Good ? **On y va.**

### C'est quoi la diff entre un site _statique_ et un site _dynamique_ ?



- Un site **statique,** c'est un peu comme ton grand-père : il raconte toujours la même chose. Par exemple, [ce petit site](http://motherfuckingwebsite.com/) que tu connais bien est un site statique, il se fiche bien de savoir qui t'es.

- Un site **dynamique,** à l'inverse, te présente un contenu qui t'es personnel. Le meilleur exemple de sites dynamiques, ce sont les réseaux sociaux : si tu te logues sur ton Instagram, ton fil d'actualité sera différent du mien. 

💡 Petite remarque, sur un même site, tu peux très bien avoir à la fois des pages statiques et des pages dynamiques. Des informations générales accessibles à tous par exemple, et un espace personnel auquel tu as accès une fois connecté.

### Le MVC, WTF ?

Le Model View Controller, MVC pour les intimes 😏, est le **modèle d'architecture** logicielle utilisé par Rails. Il fait intervenir trois composantes qui ont chacune un rôle défini et interagissent entre elles dans un cadre bien précis.

Voilà comment ça se présente :



Et ce qui se passe, étape par étape, lors du chargement d'une page dynamique :

1. Le Controller reçoit et interprête le comportement, la requête de l'utilisateur
2. Le Controller envoie une demande au Model, lequel renvoie des données vers le Controller
3. Les données en question sont dirigées vers la partie View, qui se charge de leur faire une petite beauté pour renvoyer tout ça vers l'utilisateur

**Easy,** non ?

### Les routes

Il reste une petite étape qu'on a pas évoqué au-dessus : elle se place juste après la requête de l'utilisateur.

Une page a plusieurs Controllers, et Rails utilise un système de **routing** pour envoyer les requêtes vers le Controller qui pourra les prendre en charge. Par exemple, si je souhaite commenter un article de blog, éditer mon post ou le détruire, chacune de mes requête sera traitée différement par le routeur.

Ce sera peut-être plus clair avec un petit schéma 😉

### Les bases de données

Les bases de données contiennent les informations sur lesquelles notre site repose. Par exemple, si tu contruis une application taillée pour gérer les contacts de tes utilisateurs, les informations qu'ils importeront (des noms, adresses mail, numéro de téléphone...) seront gardées bien au chaud sur une base de données.

