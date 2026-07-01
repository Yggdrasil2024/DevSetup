# Fonctionnement de la communication client serveur

dans le domaine de la communication reseaux, la communication client-serveur est le mode de fonctionnement ou des machines appelé clients dialoguent avec un serveur. c'est le model qui regit nos interactions sur le web, que se soit un email ou un tour sur youtube ou même jouer à des jeux en ligne style call of duty. ce mode de communication rend possible la centralistion des ressources et leur distribution uniforme à une multitude d'utilisateurs

# Comment se passe la communication

il s'agit d'un dialogue avec des regles strictes entre le clients et le serveur dans un cycle de requêtes et de réponses.

- Client: il s'agit de l'ordinateur de l'utilisateur qui vas envoyé une demande, une requête via une application (navigateur le plus souvent). il est toujours celui qui prend l'initiative de la communicaion. la requetes est envoyé suivant le protocol http via le reseau droit vers le serveur.

- Serveur: c'est une machine très puissante qui est en ligne en permanence au sein d'infrastucture cloud et dont le seul but est de fournir des services. il va ecouter les requetes et les traiter  et va ensuite renvoyer une reponse.

# Avantages

1. centralisation des données: l'information est stockée à un seul endroit. ce qui permet ça distribution, la gestion et la securité plus simple.

2. Scalabilité: il est possible d'ajouter la puissance ou le nombres des serveur en fonctions de la charge donc la demande coté client.

3. Administration simplifiée: les regles d'accès et les differents correctifs de securité sont appliqué au niveau du serveur mais se repercutent au niveau des postes client.

# inconvenients
  1. Point d'acces unique: si le serveur faillit, le reseau entitié vas en payer le prix comme ça été le cas avec les pannes d'AWS et CloudFlare plus tôt dans l'année.
  2. congestion du reseau: il peut y avoir une surcharge du reseau en cas d'un afflux massif et soudain d'utilisateur d'ou le besion de bonne mesure 
  3. le coût d'infrastructure: l'achat et la maintenance de telle infrastructure à un coup financier non negligéable qui est un investissement plus que conséquent pour les entreprises.

# conclusion
la communication est le pillier de la communication au sein des reseau globaux modernes. elle permet l'accessiblité, la centralisation et la distribution des ressources à très grande echelle. mais cela ammène des defis sur la resilience du reseau car centralisé, sur la scalabilité et aussi le coup financier des infrastructures.