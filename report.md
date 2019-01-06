# [Notes]

- réflexion sur la mission et la manière dont vous vous êtes organisés
- réflexion sur les choix qui ont été faits
- réflexion sur la portée de vos réalisations, leurs avantages et inconvénients, leur devenir dans l'entreprise

# Remerciements

Je tiens à remercier Guillaume Plique et Benjamin Ooghe-Tabanou pour leur très grande disponibilité tout au long du stage et pour tout ce qu'ils m'ont appris. 

# Résumé technique

Mon stage a principalement consisté en 

# 1. Le Médialab ?

## Un laboratoire un peu particulier

Le Médialab est un des 10 centres de recherche de SciencesPo. Laboratoire numérique, le Médialab a été créé en 2009 pour aider les sciences sociales et humaines à tirer le meilleur profit de la masse de données rendues disponibles par la numérisation. Ces données numériques sont au coeur des projets de recherche du labo : comment on perçoit/utilise les données numériques dans la société, ce qu'on en fait, quels outils on peut créer pour les collecter, les étudier, les exploiter, les visualiser, et ce, dans divers domaines (socio, histoire, art, ingénierie, design, pédagogie).
Il en ressort des productions de types très variés et peu courants pour un labo de sciences sociales: aux traditionnels "papiers" (articles, livres, working paper, OpEd...) s'ajoutent des applis,  des outils de collecte, d'exploration, de visualisation des données...

Constitué d'une trentaine de personnes, son équipe se distingue de celles des autres laboratoires de SciencesPo par sa grande diversité : chercheurs en sciences sociales, designers, ingénieurs pédagogiques et développeurs s'y côtoient.

Parmi les projets du laboratoire, on peut citer [La Fabrique de la Loi](https://www.lafabriquedelaloi.fr) qui propose une visualisation graphique des procédures parlementaires, le projet [Datapol](https://medialab.github.io/datapol/app/#!/) qui analyse les données numériques de la campagne présidentielle de 2017, ou [Dime Web](https://dime-shs.sciencespo.fr/instruments/dime-web/), qui vise à établir un ensemble d'outils open source permettant de collecter des données sur le web et sur les réseaux socieux (Twitter notamment).

*Laboratoires similaires ?*



## L'équipe

Paul, Guillaume, Benjamin, Jean-Philippe, Robin, Donato, Damien, Audrey, Diego

L'équipe technique du laboratoire se compose d'un directeur technique (Paul Girard), d'un ingénieur de recherche.

J'ai principalement travaillé avec Guillaume Plique, mon tuteur (développeur) et Benjamin Ooghe-Tabanou, ingénieur de recherche. 

*Donneurs d'ordre ? Comment l'info circule-t-elle ?*

*Technologies maîtrisées par l'équipe ?*

*Méthodes et outils utilisés (agile, git) ? Validation des développements (tests) ?*

# Ma mission

## Le sujet

*Sujet initial*

Le sujet global porte sur l'application des sciences des données à l'étude de l'espace public numérique.

*Ses évolutions (et leurs causes)*

*Situer le sujet dans les objectifs du labo*

*Cahier des charges précis ou participation à son élaboration ?*



## Le planning

*Vous pouvez présenter le planning initial et le planning réel avec les dates importantes.
Quelles ont été les étapes importantes ? Indiquez celles qui auraient été les plus difficiles, les plus intéressantes, etc.*

Itérations de 2 semaines.

## Mes contributions

*Etat du projet à votre arrivée ? Et à la fin ?*

*Avez-vous réalisé une étude, une maquette, une preuve de concept, un produit ou une application complète ? Que reste-t-il à faire pour rendre utilisable votre travail ?*



## Outils & technologies

*Outils, environnements, logiciels*

Tout le travail effectué l'a été en Python ou en Javascript. En Python, le gestionnaire d'environnement virtuels pyenv a été utilisé, pour compartimenter la version de Python et les dépendances de propres à chaque projet. 

Concernant les bases de données, ont été utilisés Elasticsearch (ainsi que son interface de visualisation et de monitoring Kibana) et MongoDB.

Pour le développement d'interfaces, React et material-ui ont été plébiscités, ainsi que Recharts pour la visualisation de données.

*Comment les développements ont été vérifiés/testés/validés ?*

La plupart des projets comportent des tests unitaires, qui sont vérifiés grâce au logiciel d'intégration continue Travis CI.

## Prise de recul

*Quel a été l'intérêt de votre travail pour l'entreprise ? Que va devenir votre contribution ? Présenter les perspectives.
Quelles sont les améliorations à envisager ? Quelle est la maintenance à prévoir sur cette réalisation ou cette application ?
Selon les cas, présentez vos réflexions sur **l'impact de votre travail sur les utilisateurs**, les nouveaux usages, le respect de la **vie privée** ou de l'environnement...*



# Le travail réalisé

*Cette partie est la plus longue ; vous y présenterez votre travail.
Si besoin, vous pourriez structurer le reste du rapport en plusieurs parties et non une seule. La ou les parties devraient elles-mêmes êtres structurées en plusieurs sous-sections au sein d'une même partie. Dans tous les cas, la logique du plan doit apparaître clairement.
Travaillez les liaisons pour aboutir à une lecture fluide. Voici un exemple (un peu exagéré) : "Après avoir inventorié les technologies disponibles dans la section précédente, cette section est consacrée aux expérimentations que nous avons menées avec chacune d'elles. Ce travail nous permettra de sélectionner les technologies retenues, présentées dans la section suivante."
Présentez votre réflexion et vos choix, qui devraient être justifiés. Examinez rapidement les autres alternatives.
Sélectionnez les détails pertinents et laissez les autres en annexe. Allez du général au particulier. Evitez de présenter un catalogue des fonctions développées.*

### Hyphe



### Gazouilloire

Utilisé en permanence par le laboratoire, Gazouilloire est un outil de collecte de tweets selon certains critères (mots-clés, période, langage...).

##### Pourquoi changer de base de données ?

MongoDB est un système de gestion de base de données très souple, et adapté au stockage de grandes masses de données. La limitation : la vitesse de lecture (indexation limitée), qui rend toute aggrégation impossible à partir d'une centaine de milliers de documents.

##### Comment changer de base de données ?



### HTML content extraction



### Urlsresolver



### Facebook



### Graphology



### Ural



# Conclusion

*La conclusion devrait faire de une à deux pages.
En général, on commence par présenter un résumé du rapport puis les perspectives et éventuellement les travaux restant à mener.
Vous pouvez ensuite exposer les points positifs et négatifs de votre stage.
Enfin, vous pouvez re-situer votre stage dans votre parcours de formation et dans votre projet professionnel. Vos objectifs ont-ils évolué ? Par exemple, en quoi ce stage confirme (ou infirme) votre choix de filière ?*

# Bibliographie

https://stph.scenari-community.org/contribs/nos/es3/co/es3.html 

# Glossaire

<div style="page-break-after: always;"></div>

# Annexes
