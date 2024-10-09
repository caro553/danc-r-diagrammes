```mermaid
graph TD
    %% Point de départ : Écran Home
    A[Home]

    %% Sections principales accessibles depuis Home
    A --> B[Profil]
    A --> C[Recherche]
    A --> D[Social]
    A --> E[Stats]
    A --> F[Replay]
    A --> G[Paramètres]
    A --> H[Quitter]

    %% Détails du Profil
    B --> B1[Modifier Profil]
    B --> B2[Voir Profil]
    B --> B3[Groupes]

    %% Détails de Recherche
    C --> C1[Rechercher Cours]
    C --> C2[Rechercher Coach]
    C --> C3[Rechercher Groupe]

    %% Détails de Social
    D --> D1[Groupes]
    D --> D2[Amis]
    D --> D3[Invitations]

    %% Détails des Stats
    E --> E1[Progression Générale]
    E --> E2[Statistiques par Cours]
    E --> E3[Défis]

    %% Détails de Replay
    F --> F1[Mes Replays]
    F --> F2[Replays Partagés]

    %% Détails des Paramètres
    G --> G1[Notifications]
    G --> G2[Confidentialité]
    G --> G3[Langue]
    G --> G4[Aide]
    G --> G5[À Propos]

    %% Action Quitter
    H --> H1[Confirmer Déconnexion]
