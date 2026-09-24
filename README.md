# Guide du serveur Discord Hackademy

**Rejoindre le serveur Discord : [discord.gg/pTzfwrxBQ](https://discord.gg/pTzfwrxBQ)**

Ce document est la référence du serveur pour tous : membres, Jokers et bureau. Il explique où poster quoi, qui a accès à quoi, et donne les modèles d'annonces à réutiliser toute l'année.

### En bref : où poster quoi

| Je veux… | Je vais dans… |
| --- | --- |
| Lire les infos officielles du club | `# annonces` |
| Partager un CTF, un événement, une formation trouvée ailleurs | `# partage-annonces` |
| Discuter de tout avec tout le monde | `# general` |
| Jouer un CTF en équipe et parler en vocal | Catégorie CTF |
| Parler d'une cellule ou rejoindre sa réunion | Catégorie CELLULE \<nom> |
| Voir une réunion avec un membre précis du bureau | Le vocal à son prénom dans la cellule |

## 1. Vue d'ensemble

Le serveur compte 12 catégories : un espace commun, un espace CTF, puis pour chacune des 4 cellules un espace ouvert aux membres et un espace privé réservé au bureau de la cellule, plus un espace privé pour tout le bureau. Légende : `#` = salon texte, `[voc]` = salon vocal.

```
HACKADEMY
|
|-- ACCUEIL
|   |-- # bienvenue
|   |-- # regles
|
|-- GENERAL
|   |-- # annonces              (bureau publie, les autres lisent)
|   |-- # partage-annonces      (tout le monde publie : CTF, events, formations)
|   |-- # general               (discussion libre)
|   |-- [voc] General
|
|-- CTF (ouvert a tous)
|   |-- # ctf-chat              (discussion, entraide)
|   |-- # ctf-ressources        (outils, cheat-sheets, liens)
|   |-- [voc] CTF
|
|-- CELLULE TECHNIQUE
|   |-- # technique-chat
|   |-- [voc] Reunion Technique (commune)
|   |-- [voc] Technique - Ahmad Alfadl
|   |-- [voc] Technique - Abderrahmane
|   |-- [voc] Technique - Assaad
|   |-- [voc] Technique - Nail
|-- BUREAU TECHNIQUE (prive)
|   |-- # bureau-technique-chat
|   |-- [voc] bureau-technique-reunions
|
|-- CELLULE FORMATION
|   |-- # formation-chat
|   |-- [voc] Reunion Formation (commune)
|   |-- [voc] Formation - Assaad
|   |-- [voc] Formation - Omar
|   |-- [voc] Formation - Nail
|-- BUREAU FORMATION (prive)
|   |-- # bureau-formation-chat
|   |-- [voc] bureau-formation-reunions
|
|-- CELLULE PROJETS
|   |-- # projets-chat
|   |-- [voc] Reunion Projets (commune)
|   |-- [voc] Projets - Niaama
|   |-- [voc] Projets - Ahmad Alfadl
|   |-- [voc] Projets - Houda
|   |-- [voc] Projets - Hajar
|-- BUREAU PROJETS (prive)
|   |-- # bureau-projets-chat
|   |-- [voc] bureau-projets-reunions
|
|-- CELLULE EVENEMENTIEL
|   |-- # event-chat
|   |-- [voc] Reunion Evenementiel
|-- BUREAU EVENEMENTIEL (prive)
|   |-- # bureau-event-chat
|   |-- [voc] bureau-event-reunions
|
|-- BUREAU (prive, tout le bureau)
    |-- # bureau-general
    |-- # comptes-rendus
    |-- [voc] bureau-reunions
```

Principe : chaque cellule a un espace **membres** (chat + vocal commun + un vocal par membre du bureau de la cellule, pour que deux réunions puissent avoir lieu en même temps) et un espace **bureau** privé. La cellule événementielle garde un seul vocal commun.

## 2. Rôles

Huit rôles à créer : un membre du bureau cumule `@Bureau` + le rôle de sa (ses) cellule(s), un Joker a `@Joker`, un membre du club a seulement `@Membre`.

| Rôle | Qui le reçoit | À quoi il sert |
| --- | --- | --- |
| `@Admin` | Président + Y∆W4CH | Tous les droits, gestion du serveur |
| `@Bureau` | Tous les membres du bureau | Publier dans `# annonces`, accès à la catégorie BUREAU |
| `@Bureau-Technique` | Bureau de la cellule technique | Accès à BUREAU TECHNIQUE, gère les vocaux technique |
| `@Bureau-Formation` | Bureau de la cellule formation | Accès à BUREAU FORMATION, gère les vocaux formation |
| `@Bureau-Projets` | Bureau de la cellule projets | Accès à BUREAU PROJETS, gère les vocaux projets |
| `@Bureau-Event` | Bureau de la cellule événementielle | Accès à BUREAU ÉVÉNEMENTIEL, gère le vocal event |
| `@Joker` | Amis qui aident le club, hors bureau | Accès à toutes les cellules (espaces membres et bureau de cellule) pour aider là où il faut ; pas d'accès à BUREAU ni à `# annonces` en écriture |
| `@Membre` | Tous les membres du club | Espace général, CTF et espaces membres des cellules |
| `@everyone` | Toute personne qui rejoint (non vérifiée) | Voit seulement ACCUEIL jusqu'à validation (rôle par défaut, rien à créer) |

Ordre dans la liste des rôles Discord (du haut vers le bas) : `@Admin` > `@Bureau` > rôles de cellule > `@Joker` > `@Membre` > `@everyone`.

### Composition des bureaux de cellule

| Cellule | Membres du bureau | Vocaux nominatifs |
| --- | --- | --- |
| Technique | Ahmad Alfadl, Abderrahmane, Assaad, Nail | 4 + 1 commun |
| Formation | Assaad, Omar, Nail | 3 + 1 commun |
| Projets | Niaama, Ahmad Alfadl, Houda, Hajar | 4 + 1 commun |
| Événementiel | Houda, Omar, Abderrahmane | Aucun, 1 vocal commun |

Ahmad Alfadl (Technique + Projets), Assaad et Nail (Technique + Formation) reçoivent les deux rôles de cellule correspondants.

## 3. Espace commun

Tout le club se retrouve ici ; seul `# annonces` est en lecture seule pour les membres.

### ACCUEIL

| Salon | Type | Contenu | Qui voit | Qui écrit |
| --- | --- | --- | --- | --- |
| `# bienvenue` | Texte | Message d'accueil, présentation du club | Tout le monde | Bureau |
| `# regles` | Texte | Règles du serveur, validation pour obtenir `@Membre` | Tout le monde | Bureau |

### GÉNÉRAL

| Salon | Type | Contenu | Qui voit | Qui écrit |
| --- | --- | --- | --- | --- |
| `# annonces` | Texte (ou salon Annonces) | Annonces officielles du club | Membres + Bureau | Bureau uniquement |
| `# partage-annonces` | Texte | CTF externes, événements à venir, formations, opportunités | Membres + Bureau | Membres + Bureau |
| `# general` | Texte | Discussion libre entre tous | Membres + Bureau | Membres + Bureau |
| `[voc] General` | Vocal | Vocal libre | Membres + Bureau | Membres + Bureau |

Différence clé : `# annonces` = la voix officielle du club, `# partage-annonces` = ce que n'importe qui trouve intéressant à partager.

Dans tout le document, « Membres » inclut aussi les Jokers : un Joker a toujours au moins les droits d'un membre.

### CTF

Espace ouvert à tous pour discuter des CTF et en faire ensemble en vocal.

| Salon | Type | Contenu | Qui voit | Qui écrit / parle |
| --- | --- | --- | --- | --- |
| `# ctf-chat` | Texte | CTF en cours, entraide, organisation | Membres + Bureau | Membres + Bureau |
| `# ctf-ressources` | Texte | Outils, cheat-sheets, plateformes d'entraînement | Membres + Bureau | Membres + Bureau |
| `[voc] CTF` | Vocal | Faire les CTF ensemble, partage d'écran | Membres + Bureau | Membres + Bureau |

Règle à épingler dans `# ctf-chat` : pas de flag ni de solution partagés publiquement pendant un CTF en cours.

## 4. Cellules

Chaque cellule a un espace **membres** et un espace **bureau** privé. Dans l'espace membres, un vocal commun sert quand tout le bureau de la cellule parle, et chaque membre du bureau a son propre vocal à son prénom : deux réunions peuvent donc avoir lieu en même temps dans la même cellule.

### Modèle d'une cellule (exemple : Technique)

| Catégorie | Salon | Type | Contenu | Qui voit | Qui écrit / parle |
| --- | --- | --- | --- | --- | --- |
| CELLULE TECHNIQUE | `# technique-chat` | Texte | Échanges entre membres et bureau de la cellule, supports, questions | Membres + Bureau | Membres + Bureau |
| CELLULE TECHNIQUE | `[voc] Reunion Technique (commune)` | Vocal | Réunion où tout le bureau de la cellule parle aux membres | Membres + Bureau | Membres + Bureau (`@Bureau-Technique` gère les micros) |
| CELLULE TECHNIQUE | `[voc] Technique - <Prénom>` | Vocal | Réunion animée par ce membre du bureau (son groupe, son atelier) | Membres + Bureau | Membres + Bureau (`@Bureau-Technique` gère) |
| BUREAU TECHNIQUE | `# bureau-technique-chat` | Texte | Organisation interne, planning, répartition des tâches | `@Bureau-Technique` + Jokers + Admin | idem |
| BUREAU TECHNIQUE | `[voc] bureau-technique-reunions` | Vocal | Réunions internes du bureau de la cellule | `@Bureau-Technique` + Jokers + Admin | idem |

### Les 4 cellules

| Cellule | Espace membres | Espace bureau | Rôle du bureau |
| --- | --- | --- | --- |
| Technique | `# technique-chat` · `[voc] Reunion Technique (commune)` · `[voc] Technique - Ahmad Alfadl` · `[voc] Technique - Abdrahman` · `[voc] Technique - Assaad` · `[voc] Technique - Nail` | `# bureau-technique-chat` · `[voc] bureau-technique-reunions` | `@Bureau-Technique` |
| Formation | `# formation-chat` · `[voc] Reunion Formation (commune)` · `[voc] Formation - Assaad` · `[voc] Formation - Omar` · `[voc] Formation - Nail` | `# bureau-formation-chat` · `[voc] bureau-formation-reunions` | `@Bureau-Formation` |
| Projets | `# projets-chat` · `[voc] Reunion Projets (commune)` · `[voc] Projets - Niaama` · `[voc] Projets - Ahmad Alfadl` · `[voc] Projets - Houda` · `[voc] Projets - Hajar` | `# bureau-projets-chat` · `[voc] bureau-projets-reunions` | `@Bureau-Projets` |
| Événementiel | `# event-chat` · `[voc] Reunion Evenementiel` | `# bureau-event-chat` · `[voc] bureau-event-reunions` | `@Bureau-Event` |

### BUREAU (tout le bureau)

| Salon | Type | Contenu | Qui voit / écrit |
| --- | --- | --- | --- |
| `# bureau-general` | Texte | Coordination entre cellules, décisions du club | `@Bureau` + Admin |
| `# comptes-rendus` | Texte | PV des réunions, décisions archivées | `@Bureau` + Admin |
| `[voc] bureau-reunions` | Vocal | Réunions générales du bureau | `@Bureau` + Admin |

## 5. Matrice des droits d'accès

Les permissions se règlent au niveau de la **catégorie**, puis les salons se synchronisent dessus ; seul `# annonces` a une exception.

Légende : **Gérer** = voir, écrire, supprimer des messages, rendre muet · **Écrire** = voir + écrire / parler · **Lire** = voir sans écrire · **–** = invisible.

| Catégorie / salon | @everyone | @Membre | @Joker | @Bureau | @Bureau-\<cellule> concerné | @Admin |
| --- | --- | --- | --- | --- | --- | --- |
| ACCUEIL | Lire | Lire | Lire | Gérer | – | Gérer |
| GÉNÉRAL (hors annonces) | – | Écrire | Écrire | Gérer | – | Gérer |
| `# annonces` | – | Lire | Lire | Gérer | – | Gérer |
| CTF | – | Écrire | Écrire | Gérer | – | Gérer |
| CELLULE \<X> (espace membres, vocaux compris) | – | Écrire | Écrire | Écrire | Gérer | Gérer |
| BUREAU \<X> (espace privé cellule) | – | – | Écrire | – | Gérer | Gérer |
| BUREAU (tout le bureau) | – | – | – | Gérer | – | Gérer |

Point clé : un membre du bureau technique **ne voit pas** BUREAU FORMATION, car seul `@Bureau-Formation` y a accès, pas `@Bureau`.

### Permissions Discord à cocher

| Niveau | Permissions Discord |
| --- | --- |
| Lire | Voir le salon, Lire l'historique · refuser Envoyer des messages, Réagir (optionnel) |
| Écrire | Voir le salon, Envoyer des messages, Joindre des fichiers, Intégrer des liens, Se connecter, Parler, Vidéo/partage d'écran |
| Gérer | Écrire + Gérer les messages, Épingler, Rendre muet, Déplacer des membres, Mentionner @everyone |

## 6. Modèles d'annonces

Copier le modèle, remplacer ce qui est entre `[CROCHETS]`, publier dans `# annonces` (ou le salon indiqué).

| Type | Qui est concerné | Où se tient la réunion | Où publier l'annonce | Qui taguer |
| --- | --- | --- | --- | --- |
| Événement du club | Tout le club | Lieu de l'événement | `# annonces` | `@Membre` `@Joker` @Bureau |
| Réunion générale du club | Tout le club + tout le bureau | Salle ou `[voc] General` | `# annonces` | `@Membre` `@Joker` @Bureau |
| Réunion de cellule (commune) | Membres + tout le bureau de la cellule | `[voc] Reunion <Cellule> (commune)` | `# annonces` | `@Membre` `@Joker` @Bureau-\<Cellule> |
| Réunion interne d'un bureau de cellule | Bureau de la cellule (+ Jokers) | `[voc] bureau-<cellule>-reunions` | `# bureau-<cellule>-chat` | `@Bureau-<Cellule>` |
| Réunion du bureau | Tout le bureau | Salle ou `[voc] bureau-reunions` | `# bureau-general` | `@Bureau` |

### Événement du club

```
@Membre @Joker @Bureau
**[EVENEMENT] [NOM]**
Date : [JJ/MM] a [HH:MM]
Lieu : [LIEU]
[1 LIGNE DE DESCRIPTION]
Inscription : [LIEN]
```

### Réunion générale du club

```
@Membre @Joker @Bureau
**[REUNION GENERALE] [SUJET]**
Date : [JJ/MM] a [HH:MM]
Lieu : [SALLE] / vocal General
```

### Réunion de cellule (commune)

```
@Membre @Joker @Bureau-<Cellule>
**[CELLULE <NOM>] Reunion : [SUJET]**
Date : [JJ/MM] a [HH:MM]
Vocal : Reunion <Nom> (commune)
```

### Réunion interne d'un bureau de cellule

Dans `# bureau-<cellule>-chat` :

```
@Bureau-<Cellule>
**Reunion bureau <cellule> : [SUJET]**
Date : [JJ/MM] a [HH:MM]
Vocal : bureau-<cellule>-reunions
```

### Réunion du bureau

Dans `# bureau-general` :

```
@Bureau
**Reunion du bureau : [SUJET]**
Date : [JJ/MM] a [HH:MM]
Lieu : [SALLE] / vocal bureau-reunions
```
