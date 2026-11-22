# FocusFlow

Application web progressive de concentration et suivi du temps, avec espaces **Professionnel** et **Personnel**.

## Fonctionnement

- Minuteurs Pomodoro 25 min, Deep Work 50 min et mode libre.
- Pause/reprise, interruptions, note de concentration en fin de session.
- Historique et statistiques par espace.
- Sauvegarde/import JSON et export CSV.
- Stockage local au navigateur (`localStorage`) : aucun serveur de données.
- Installation sur écran d'accueil et cache hors ligne après une première visite en ligne.

## Publier avec GitHub Pages

1. Créer un dépôt public `focusflow` et déposer tous les fichiers de ce dossier **à la racine** de `main`.
2. GitHub → **Settings → Pages** → **Deploy from a branch** → **main** → **/(root)** → Save.
3. Ouvrir `https://VOTRE-IDENTIFIANT.github.io/focusflow/` dans Safari.
4. Sur iPhone : **Partager → Sur l'écran d'accueil**.

## Confidentialité et limites

- Le dépôt public expose le code source, **pas les sessions** : celles-ci sont conservées sur l'appareil, dans l'espace de stockage du navigateur.
- Les données ne se synchronisent pas automatiquement entre appareils ni entre navigateurs.
- Effectuer régulièrement un export JSON. Effacer les données Safari peut supprimer les sessions.
- Le chronomètre peut se remettre à jour après un retour dans l'application, mais iOS peut suspendre JavaScript en arrière-plan : pas de notification de fin de session garantie.
- Une session non terminée n'est pas sauvegardée si la page est fermée/rechargée.
- Éviter de saisir des informations professionnelles confidentielles dans les titres et notes.
