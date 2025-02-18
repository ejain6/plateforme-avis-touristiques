# Création d'une Plateforme d'Avis et Conseils Touristiques (PACT)

## Conxtexte et enjeux du projet

Ce projet fut réalisé dans le cadre de la 2ème année du BUT informatique, le but étant de mettre nos compétences, notamment le  <b>développement web</b> et la gestion de <b>bases de données</b>, en application sur un projet concret et durant sur le long terme.

Ce projet nous a effectivement suivi du mois d'octobre 2024 au mois de janvier 2025, soit la quasi totalité du semestre, avec la suite et fin de <i>l'aventure</i> arrivant durant le de mars 2025, sur 4 semaines.


## Réalisation du projet

### Gestion de projet

La création de cette plateforme s'est faite avec une équipe de 7 membres, <i>puis 6, voire 5...</i>, dirigée agilement avec la <b>méthode Scrum</b>, dont j'érais le <b>Product Owner</b>. 
Nous avons réalisés <b>4 sprints de 2 à 3 semaines</b> répartis sur le semestre, durant lesquels nous appliquions donc la méthodologie Scrum, réalisant les planing meetings, daily meetings, reviews et rétros (en utilisant <b>Jira</b> comme outil de Gestion)


### Analyse du besoin client

#### Story Mapping

Tout bon projet débute par le recueil et l'analyse des besoins des clients, c'est donc ce que l'on a logiquement fait, et qui nous a permis plusieurs choses : 
- <b>Organiser l'équipe</b> et définir les rôles de Scrum master et Product Owner
- <b>Spécifier les besoins</b>, en les décomposeant les en "User Stories"
- <b>Estimer la charge de travail</b> de ces User Stories <i>(pas une mince affaire pour des débutants...)</i>
- <b>Définir l'importance</b> de ces US, pour savoir lesquelles réaliser d'abord

Tout cela a donc créé notre <b>Product Backlog</b> sur Jira dont j'étais le respobsable en tant que Product Owner. Le Product Backlog contient toutes les User Stories, qui sont donc estimées en complexité et en priorité et regroupées par thématiques

#### Conception du projet

Après avoir analysé le besoin du client, nous avions donc une idée abstraite du projet qui nous attendait. Il nous fallait mainenant concrétiser cette idée en concevant les différentes faces du site web. Pour cela nous avons réalisé :
- <b>Une [charte graphique](conception/A21_CharteGraphique.pdf)</b>, pour donner une identité graphique à la plateforme et s'y tenir
- <b>Une [maquette Figma](conception/A21_maquetteV2.pdf)</b>, pour donner une 1ere idée au client de l'interface graphique, puis s'y tenir en l'adaptant en fonction des retours du client
- <b>Un [diagramme UML](conception/A21_DiagrammeClasseUMLfinal.jpg) et un [dictionnaire de données](conception/A21_DictionnaireDesDonnées.xlsx)</b> pour modéliser la base de données qui servira a stocker les données nécessaires au fonctionnement de la plateforme


### Lancement des Sprints 

#### Planning Meeting

À chaque début de sprint, il faut <b>choisir parmi toutes les User Stories du Product Backlog</b> lesquelles seront développées durant le sprint. Excepté au 1er sprint, l'importance des US est réévaluée car des US ont été développées au dernier sprint, tandis que certaines ont possiblement été supprimées et d'autres ajoutées, <i>notamment des bugs a régler...</i>
Les US choisies pour le sprint <b>doivent toutes être développées</b> en temps et en heure, sans qu'on arrive trop vite à court de travail avant la fin.

C'est donc comme ca que l'on réalise le <b>Sprint Backlog</b> au debut de chaque sprint, après quoi le travail peut vraiment débuter.

#### Approfondissement des User Stories

Une fois le sprint lancé, il faut commencer par détailler les US du Sprint Backlog en leur attribuant des <b>histoires utilisateur</b>, détaillant le parcours de l'utilisateur qui utilise la fonctionnalité par des exemples.

Il faut également ajouter des <b>critères d'acceptation</b> aux US choisies. Ces derniers, qui sont des <b>critères de réussite ou d'échec</b>, précisent quelles sont les conditions pour que la fonctionnalités aboutisse ou non. Grâce à ça, des tests selon les critères d'acceptation pourront être effectués pour vérifier si l'US est bien développée ou non.


### Durant les sprints

Après avoir suffisament approfondi ses User Stories, on peut commencer à <b>les développer</b>, par ordre d'importance. Ces fonctionnalités sont découpées de sorte à ce qu'un membre puisse les gérer seul sans y passer un temps excessif, <i>pour un développeur COMPÉTENT bien entendu...</i>

Pour se tenir au courant sur l'avancée de l'équipe, un <b>Stand-up Meeting / Daily Meeting</b> est réalisé, chaque jour, debout, <i>comme ses noms l'indiquent.</i> Le but de ces micro-réunions quotidiennes est que chaque membre explique aux autres en 2 minutes maximum :
- Ce qu'il a <b>fait la veille</b>
- Les <b>problèmes rencontrés</b>, sans y rentrer en détails
- Ce qu'il <b>prévoit de faire</b> aujourd'hui

Durant chaque sprint, nous avons donc développé nos US chacun de notre côté, en se tenant à jour avec les Daily Meetings. Le Scrum Master a souvant aidé les membres qui bloquaient sur leurs US, mais il y avait égalament de l'entraide entre les membres eux même, <i>sinon le SM n'aurait pas pu beaucoup travailler...</i>


### À la fin des sprints

#### La Sprint Review

Si toutes les User Stories prévues ont été développées, nous avons donc une realease (la nouvelle version) telle que prévu. Cette realease est présentée au client au cours de la <b>Review</b>, ou je (Product Owner) réalisais une <b>démonstration du site</b>, accompagné des membres de l'équipe, car chacun montrait généralement ce qu'il avait produit. La présentation des nouveutés de la plateforme durait généralement une vingtaine de minutes, suivie d'une quarantaine de minute <b>d'interractions avec le(s) client(s)</b> afin de parler de ce qui va, et de ce qui ne va pas. 

Ces interractions avec le client permettent de rester dans le <b>droit chemin à propos de ses attentes</b>, car les besoins peuvent changer en cours de projet, et l'équipe peut être passé à coté de certains points sans s'en rendre compte. C'est d'ailleurs pour cela que les méthodes Agiles sont pratiques et répandues, car l'interraction avec le client va mener à réaliser un produit final <b>tel qu'il l'avait immaginé</b> ou presque, et donc le satisfaire.

#### La Rétrospective

Après que le sprint ait pris fin, une <b>Rétrospective</b> est organisée, réunissant tous les membres de l'équipe dans le but de <b>réfléchir au fonctionnement</b> du projet et d'<b>améliorer la productivité</b> du groupe pour les prochains sprints. Les membres vont donc dire quel(le)s ont été pour eux : Les <b>forces</b> de l'équipe / Ses <b>faiblaisses</b> / Ce qui a <b>marché</b> / Ce qui n'a <b>pas marché</b> / Ce qu'ils pourraient <b>améliorer</b>. Mettre tous ces éléments en commun va servir a <b>trouver un ou deux axes d'amélioration</b> pour le prochain Sprint, afin de d'améliorer.