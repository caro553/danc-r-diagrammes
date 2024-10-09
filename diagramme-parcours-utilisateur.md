```mermaid
graph TD
    %% Sections principales depuis la page Home
    A[Home] --> B[Profil]
    A --> C[Recherche]
    A --> D[Chat]
    A --> E[Mes Stats]
    A --> F[Mes Replays]
    A --> G["Ajouter (+)"]

    %% Détails du Profil
    B --> B1[Modifier Profil]
    B --> B2[Paramètres]
    B --> B3[Quitter Groupe]

    %% Détails des Paramètres
    B2 --> B2a[Notifications]
    B2 --> B2b[Confidentialité]
    B2 --> B2c[Langue]
    B2 --> B2d[Aide]
    B2 --> B2e[Déconnexion]

    %% Recherche
    C --> C1[Rechercher Cours]
    C --> C2[Rechercher Coach]
    C --> C3[Rechercher Groupe]
    C1 --> C1a[Liste des Cours]
    C2 --> C2a[Liste des Coachs]
    C3 --> C3a[Liste des Groupes]

    %% Groupe
    D --> D1[Conversations]
    D --> D2[Groupes]
    D1 --> D1a[Nouvelle Conversation]
    D2 --> D2a[Nouveau Groupe]

    %% Mes Stats
    E --> E1[Progression Générale]
    E --> E2[Statistiques par Cours]
    E1 --> E1a[Graphiques]
    E1 --> E1b[Historique]

    %% Mes Replays
    F --> F1[Revoir Sessions]
    F --> F2[Supprimer Replays]

    %% Ajouter (+)
    G --> G1[Commencer Nouveau Cours]
    G --> G2[Enregistrer Session]
    G --> G3[Créer Groupe]
    G --> G4[Inviter Amis]
