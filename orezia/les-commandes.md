---
description: >-
  Tu peux retrouver ici toutes les commandes disponibles sur Orezia. Certaines
  sections redirigent directement vers la page dédié.
hidden: true
---

# Les Commandes

> Les commandes sont présentées ainsi : /commande \[variable obligatoire] \<variable facultatif>

{% hint style="warning" %}
Certaines commandes ne fonctionnent pas à 100% pour les **Bedrock Edition**, car celles-ci demandent de cliquer dans le chat pour confirmer. Il existe pour cela des commandes alternatives.
{% endhint %}

## **Commandes principales**&#x20;

### **Communes**

* **/serveur** : Permet de se déplacer entre les différents serveurs d'Orezia.
* **/discord** : Lien vers le Discord d'Orezia.
* **/site** : Lien vers le site d'Orezia.
* **/wiki** : Lien vers le wiki d'Orezia.

### **Messagerie**

* **/msg \[pseudo] \[message]** : Envoie un message privé à un joueur en ligne.
* **/r \[message]** : Répond au dernier message privé reçu.
* **/ignore \[pseudo]** : Permet d'ignorer un joueur. Tu ne verras plus ses messages publics, et celui-ci ne peut plus vous envoyer de messages privés.
* **/me \[message]** : Permet d'écrire un message d'humeur. Celui-ci ne doit pas être utilisé pour parler entre joueurs.

## Commandes Semi-RP

### Se déplacer

* **/spawn** : Téléporte le joueur au spawn du serveur.
* **/home \[nom]** : Téléporte le joueur à la position sauvegardée.
* **/homes** : Ouvre le menu de ses positions sauvegardées.
* **/sethome \[nom]**  : Sauvegarde la position du joueur avec le nom indiqué.
* **/delhome \[nom]** : Supprime la position du joueur avec le nom indiqué.
* **/rt** : Ouvre le menu pour se téléporter aléatoirement dans le monde Ressource.
* **/tpaccept** :  Accepte la requête de téléportation reçue.
* **/tpdeny** : Refuse la requête de téléportation reçue.

### **Économie**

* **/orez** : Permet de voir tes différentes soldes.
* **/trade \[pseudo]** : Envoie une demande d'échange au joueur. Le menu d'échange permet d'échanger en sécurité des ressources et/ou des orez. Deux joueurs proches peuvent aussi accroupi + clic droit l'un sur l'autre pour envoyer la demande. \
  Il est possible de l'accepter avec la commande **/trade accept** ou de la refuser avec **/trade deny**. Il y est aussi possible de bloquer les demandes avec **/trade toggle**.
* **/apay \[pseudo] \[montant]** : permet d'envoyer de points animaux à un joueur.

### **Messagerie**

* **/mail** : Indique si tu as des mails
* **/recrute \<message>** : Envoie un message dans le canal de recrutement. Temps de recharge de 1 heure. Il est possible de l'activer en permanent sans mettre de message après la commande.
* **/commerce \<message>** : Envoie un message dans le canal de commerce. Temps de recharge de 1 heure. Il est possible de l'activer en permanent sans mettre de message après la commande.
* **/general** : Permet de revenir dans le canal principal, dans la cas où tu as activé un canal en permanent.

### **Divers**

* **/metier** : Ouvre le menu Métier. Celui-ci permet d'avoir plusieurs informations : ton niveau de métier, ton expérience, les actions rémunérées par métier, ta limite d'expérience à l'heure, le top de chaque métier, les différents objets liés (alambic, fourneau, fumoir et haut fourneau), et savoir si un Orus (bonus d'expérience métier) est en cours et jusqu'à quelle heure.
* **/voter** : Ouvre le menu des votes.
* **/animaux** : Ouvre la boutique des animaux, pour acheter un animal contre des points animaux.
* **/cosmetique** : Ouvre le menu des cosmétiques.
* **/quest** : Ouvre le menu des quêtes, il te permet de voir les quêtes en cours.
* **/quest scoreboard** : Désactive le scoreboard des quêtes.
* **/rang** : Permet de connaître les étapes ainsi que les prérequis pour le rang supérieur.
* **/rangville** : Permet de connaître les étapes ainsi que les prérequis pour le rang supérieur de la ville .
* **/playtime** : Permet de connaître ton temps de jeu.
* **/playtimeshop** ou **/ptshop** : Ouvre la boutique de temps de jeu. Celle-ci permet d'utiliser du temps de jeu pour acheter certaines ressources/items.
* **/donate accept \<pseudo>** : Montre la liste des items envoyé par un grade Elite en attente d'acceptation. Si tu indiques le pseudo, accepte la demande du joueur.

{% hint style="warning" %}
Le **temps de jeu est consommé** lors d'un achat dans la boutique de temps de jeu, donc fais attention lorsque tu es propriétaire d'une ville, cela à un **impact important** dessus.
{% endhint %}

### **Trier**

{% hint style="info" %}
Le tri te permet de téléporter automatiquement les items de ton inventaire dans les coffres alentours sur lesquels sont configurés des filtres.

* Seuls les coffres, double-coffres et tonneaux peuvent contenir des filtres.
* Le tri a une portée limitée, dépendant du type choisi.
* Les items sont placés en priorité dans les conteneurs ayant un filtre avec une priorité plus basse, puis dans les conteneurs les plus proches.
* Les items enchantés ne sont pas différenciés, autrement dit une épée en bois et une épée en bois enchantée sont considérées comme les mêmes items.
{% endhint %}

* **/trier \<type>** : Ouvre le menu affichant les différents tris possibles. Si un type est indiqué, il sera effectué directement sans ouvrir le menu.&#x20;
* **/filtre** : Ouvre le menu du filtre du conteneur visé.&#x20;
* **/filtre blacklist** : Ouvre le menu de la liste noire. Les items de la liste noire ne seront pas triés dans les coffres alentour.&#x20;
* **/filtre copie** : Copie le filtre du conteneur visé, te permettant de l’appliquer sur plusieurs conteneurs rapidement en faisant un clic gauche sur eux. La copie se termine en faisant un clic gauche sur n’importe quel bloc qui n’est pas un conteneur.&#x20;
* **/filtre generer** : Crée automatiquement un filtre à partir des items déjà placés dans le conteneur visé. Si un filtre est déjà configuré sur le conteneur, il sera écrasé.&#x20;
* **/filtre generation** : Active la génération de filtres par clic gauche sur des conteneurs (_voir commande `/filtre generer`_). Si aucune option n’est indiquée, la génération s’active si elle est désactivée et vice-versa. La génération se termine en faisant un clic gauche sur n’importe quel bloc qui n’est pas un conteneur.&#x20;
* **/filtre priorite \[priorite|defaut]** : Applique la priorité indiquée sur le filtre du conteneur visé. La priorité est un entier compris entre 0 et 20 inclus. L’option `defaut` réinitialise la priorité du filtre à celle par défaut. Il est possible de voir la priorité d’un filtre en ouvrant son menu (_voir commande `/filtre`_).&#x20;
* **/filtre priorisation \[priorite|defaut]** : Active/désactive la priorisation de filtre par clic gauche sur des conteneurs (_voir commande `/filtre priorite`_). La priorisation se termine en faisant un clic gauche sur n’importe quel bloc qui n’est pas un conteneur.&#x20;
* **/filtre rapide** : Active/désactive l’ouverture rapide des filtres. Lorsque cette option est activée, effectuer un clic droit sur un conteneur ouvrira son filtre au lieu de son inventaire.
* **/filtre restreindre** : Restreint/libère le filtre du conteneur visé. Restreindre un filtre signifie qu’il est impossible de placer dans le conteneur un item qui n’est pas configuré dans son filtre. Il est possible de voir si un filtre est restreint en ouvrant son menu (_voir commande `/filtre`_).&#x20;
* **/filtre restriction \[vrai|faux]** : Active la restriction/libération de filtres par clic gauche sur des conteneurs (_voir commande `/filtre restreindre`_). La restriction se termine en faisant un clic gauche sur n’importe quel bloc qui n’est pas un conteneur.&#x20;
* **/filtre supprimer** : Supprime le filtre du conteneur visé. Détruire un conteneur supprime automatiquement son filtre.&#x20;
* **/filtre suppression** : Active la suppression par clic gauche sur des conteneurs (_voir commande `/filtre supprimer`_). La suppression se termine en faisant un clic gauche sur n’importe quel bloc qui n’est pas un conteneur.

### **Liens** **utiles**

* **/regles** : Lien vers le règlement du serveur
* **/map** : Lien vers la map 3D du monde Orezia
* **/voter** : Ouvre le menu des votes, celui-ci permet d'accéder aux différents liens, à la boutique de vote, ainsi qu'avoir des informations tels que ton nombre de votes.

### **Boutique**

* **/avantages** : Permet de connaître les avantages des grades premium directement en jeu.
* **/boutique** : Ouvre la boutique en jeu.

### **Les villes**

{% content-ref url="../guides/les-villes.md" %}
[les-villes.md](../guides/les-villes.md)
{% endcontent-ref %}

### **L'échange et les échoppes**

{% content-ref url="../guides/leconomie/le-commerce.md" %}
[le-commerce.md](../guides/leconomie/le-commerce.md)
{% endcontent-ref %}

## Commandes Créatif

{% content-ref url="/broken/pages/1b3tgwMCG7yiB3GYRO0U" %}
[Broken link](/broken/pages/1b3tgwMCG7yiB3GYRO0U)
{% endcontent-ref %}

## **Commandes Premium**

### Neophyte

#### Commune :

* **/se \[ligne] \<texte>** : Permet d'éditer un panneau sans avoir à le détruire. Si le texte n'est pas indiqué, supprime le contenu de la ligne.
* **/sc** : Permet de copier un panneau pour coller son contenu sur un autre panneau
* **/colors** : Affiche dans le tchat les codes couleurs et de formatage du texte​
* **/sit** : Permet de s'asseoir en jeu, sur n'importe quel bloc. Un double clique droit sur des dalles permet de s'asseoir directement.

#### Semi-RP :

* **/back** : Permet de revenir au dernier emplacement avant une téléportation (spawn, home). La commande ne permet pas de revenir à son lieu de mort !
* **/hdv** : Ouvre le menu de l'Hôtel des Ventes depuis n'importe où.

### Elite

#### Commune :

* **/tpa \[pseudo]** : Permet de te téléporter à un autre joueur, s'il ou elle accepte.
* **/tpahere \[pseudo]** : Permet de téléporter un autre joueur à ta position, s'il ou elle accepte.
* **/armorstand** : Permet d'éditer un porte-armure le plus proche. Un accroupi + clique droit permet aussi de l'éditer.

#### Semi-RP :

* **/ascenseur** : Permet de créer un bloc ascenseur en dessous de soi.
* **/donate \[pseudo]** : Permet d'envoyer à n'importe quel autre joueur l'item porté en main. Une seule demande à la fois. L'échange se fait qu'inter-monde (Ressource vers Ressource, ou Orezia vers Orezia).
* **/opay \[pseudo] \[montant]** : Permet d'envoyer de l'argent à distance à un joueur en ligne.
* **/vol** : Ouvre le menu du vol. Permet de voler dans son terrain ou un terrain acceptant le vol.
* **/wb** ou **/workbench** : Ouvre une table de craft portative.
* **/hat** : Permet de mettre n'importe quel item en tant que casque. Si tu portes déjà un casque, celui-ci sera remplacé par l'item choisi.
* **/ec** : Permet d'accéder à son coffre de l'ender depuis n'importe où.

## **Boutique**

### **La banque portative**

* **/banque** : permet d'accéder à ta banque depuis n'importe quel monde. Si tu n'as pas le grade Neophyte minimum, tu n'auras pas accès au stockage d'expérience.

### **Les mini-bloc**

* **/hdb** : ouvre le menu des mini-blocs (+ 35 000)
* **/hdb search** : permet de faire une recherche par rapport à un mot-clé
