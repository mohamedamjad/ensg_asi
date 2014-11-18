Architectures distribuées:
===
- RMI est assez répondu actuellement
- Problématique de la distribution: Cohérence de l'information exemple de plusieurs boutiques avec un seul centre de gestion de stock, au cas ou il y a plusieurs clients qui se pointent en meme temps.
Concurrence des actions: ressources dans une architecture distribuées sont limités.
- Problématique de complexité: distribuer ça rend els chsoes + compliquées
-Exemple des SGBDR - ACID: Atomicité(action ne peut pas être encore découpée), Cohérence(réponse cohérente), Isolation, Durabilité.
- Pourquoi distribuer ?:
  - Notion de (Haute) disponibilité: (d) important : CONFIANCE JUSTIFIEE
  
Virtualisation:
====
- Virtualisation des applications: une couche d'apstraction permet de rendre les applications indépendantes des OS
  - Wine, JVM, Languages interprétés
- Virtualsiation du réseau: on partage le physique et on masque aux usilisateurs la virtualsiation. Onparle alors de VLAN Virtual LAN.
- Virtualisation du stockage: Généralisation de la notion de partitions sur des agrégations réparties (d)
  - Ajout de disque/supression de disque sans coupure
- Virtualsiation des serveurs: ...

Avantages de la Virtualisation
===
- Optimisation de l'utilsiation des ressources
- moins de dépenses énergétiques
- Meilleure reprise sur erreur
- Flexibilité des applications: un morceau là, un morceau là, un morceau là.

Inconvénients de la virtualsiation:
===
- complexité analytique accrue: si quelque chose se passe côté matériel très dur de comprendre ce qui s'est passé
- dégradation des performances I/O... (voir d)
- Pas de standards sur la virtualisation
- 
Types de virtualsiations
===

- Machines virtuelles (type1/type2): VMWare, VBox | machine compléte 
- Para-virtualisation: plus performante, vient du monde libre, probleme d'interoperabilité
- Containeurs (des éléments de l'OS avec nous mais pas le matériel simulé): performances quasi-natives, mais dépend du systeme d'exploitation sur le quel il tourne: un container linux tourne sur linux, un windows tourne sur windows
