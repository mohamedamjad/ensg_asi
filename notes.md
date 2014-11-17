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
