# project-ldap-isestma
Étude et modélisation d’un service d’annuaire LDAP pour le campus universitaire ISESTMA — BTS Niveau 2 Réseaux et Sécurité.



Écriture
Projet LDAP — Campus universitaire ISESTMA
1. Présentation du projet
Ce projet s’inscrit dans le cadre du cours Authentification des services d’annuaire et administration des systèmes d’exploitation réseaux, dans le cadre du BTS Niveau 2 Réseaux et Sécurité.
Il porte sur l’étude et la modélisation d’un service d’annuaire LDAP adapté au contexte d’un campus universitaire : l’Institut Supérieur d’Études Scientifiques, Technologiques et Managériales (ISESTMA).
L’objectif est de proposer une organisation logique permettant de structurer les comptes utilisateurs, les groupes, les machines et les services informatiques de l’établissement.
2. Objectifs du projet
Les principaux objectifs sont :
Identifier les entités à intégrer dans l’annuaire.
Construire l’arbre DIT (Directory Information Tree).
Comprendre les DN (Distinguished Name) et les RDN (Relative Distinguished Name).
Analyser les classes d’objets et les attributs LDAP obligatoires et facultatifs.
Reconstituer un scénario d’authentification et de recherche LDAP.
Proposer un modèle d’annuaire adapté aux besoins du campus.
Préparer la mise en pratique avec OpenLDAP et les fichiers LDIF.
3. Documents du projet
Le dépôt contient les cinq documents suivants :
Document 1 — Liste des entités du projet
Fichier : 01_liste_entites_projet_annuaires_ISESTMA.pdf
Identification et organisation des entités à intégrer dans l’annuaire : étudiants, enseignants, personnel administratif, groupes, machines et services.
Document 2 — Construction de l’arbre DIT
Fichier : 02_arbre_DIT_campus_ISESTMA.pdf
Présentation de la structure hiérarchique de l’annuaire LDAP, avec les unités organisationnelles, les DN, les RDN et les entrées associées.
Document 3 — Fiches d’analyse des entrées LDAP
Fichier : 03_fiches_analyse_entrees_LDAP_ISESTMA.pdf
Étude des entrées LDAP, de leurs classes d’objets, de leurs attributs obligatoires (MUST), de leurs attributs facultatifs (MAY) et de leur validité.
Document 4 — Scénario LDAP reconstitué
Fichier : 04_scenario_LDAP_reconstitue_ISESTMA.pdf
Analyse d’un scénario comprenant les opérations d’authentification (bind), de recherche (search) et de fermeture de session (unbind), ainsi qu’un exemple de modification d’attribut au format LDIF.
Document 5 — Modèle d’annuaire argumenté
Fichier : 05_modele_annuaire_argumente_ISESTMA.pdf
Présentation du modèle final proposé, justification des choix de conception, comparaison entre OpenLDAP, Active Directory et une architecture hybride, et exemple de création d’unités organisationnelles avec LDIF.
4. Technologies et notions étudiées
LDAP (Lightweight Directory Access Protocol)
OpenLDAP
Active Directory
DIT, DN et RDN
Classes d’objets et attributs LDAP
Fichiers LDIF
Authentification et recherche dans un annuaire
Commandes ldapadd, ldapsearch et ldapmodify
5. Organisation du dépôt
projet-ldap-isestma/
├── README.md
├── 01_liste_entites_projet_annuaires_ISESTMA.pdf
├── 02_arbre_DIT_campus_ISESTMA.pdf
├── 03_fiches_analyse_entrees_LDAP_ISESTMA.pdf
├── 04_scenario_LDAP_reconstitue_ISESTMA.pdf
└── 05_modele_annuaire_argumente_ISESTMA.pdf
6. Périmètre et précautions
Ce projet constitue une étude pédagogique et une proposition de modélisation d’un annuaire LDAP pour le campus universitaire ISESTMA.
Les noms de comptes, les noms de machines et le domaine dc=isestma,dc=cm utilisés dans les exemples sont des éléments de démonstration qui doivent être validés avant toute mise en œuvre réelle.
Les classes d’objets et les attributs devront également être vérifiés selon les schémas LDAP installés sur le serveur utilisé.
7. Conclusion
Ce projet permet d’étudier les principes fondamentaux des services d’annuaire LDAP et leur application à l’organisation des identités et des ressources informatiques d’un campus universitaire.
Il constitue une base de travail pour une future mise en œuvre pratique avec OpenLDAP, la création d’entrées LDIF et les tests d’authentification et de recherche.
Projet académique : Campus universitaire ISESTMA
Filière : Réseaux et Sécurité
Niveau : BTS Niveau 2
Thème : Authentification des services d’annuaire et administration des systèmes d’exploitation réseaux
