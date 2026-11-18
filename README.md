# Habitudes 🌸

Petite web-app minimaliste (couleurs pastel) pour suivre ses bonnes habitudes sur iPhone.

- **À faire** : trois blocs — *Aujourd'hui*, *Cette semaine*, *Ce mois-ci*.
- Récurrences libres : « X fois tous les N jours / semaines / mois »
  (ex. 2×/jour, 2×/semaine, 1× tous les 2 mois, 1× tous les 3 mois…).
- Une tâche cochée reste cochée jusqu'au début de son prochain cycle
  (minuit, lundi, 1er du mois, ou tous les N mois à partir de la date de début choisie).
- **Jauge du mois** (« 10 sur 15 ») en haut de la page et dans le bilan, avec un repère pour le jour actuel.
- **Bilan du mois** : ce qui a été fait pendant le mois en cours (remis à zéro chaque mois, pas d'historique).
- Bouton en haut à droite : ajouter / modifier / supprimer les habitudes, sauvegarde et restauration (fichier JSON).
- Fonctionne hors-ligne, données stockées sur le téléphone.

## Installer sur iPhone

1. Sur GitHub : **Settings → Pages → Build and deployment** : Source « Deploy from a branch »,
   choisir la branche (ex. `main`) et le dossier `/ (root)`, puis **Save**.
2. Ouvrir l'URL donnée (`https://<utilisateur>.github.io/Tracker-/`) dans **Safari** sur l'iPhone.
3. Bouton **Partager** → **Sur l'écran d'accueil**. L'app s'ouvre ensuite en plein écran comme une vraie app.

Aucune dépendance, aucun build : tout est dans `index.html`.

---

# Budget de la semaine 💶

Deuxième petite app, dans le dossier `budget/` (`https://<utilisateur>.github.io/Tracker-/budget/`).

- Une **limite par semaine** pour chaque catégorie : *Courses*, *Shopping*, *Martin*, *Autres*
  (le budget total de la semaine = la somme des limites).
- **Reste à dépenser** de la semaine, et pour chaque catégorie ce qui reste ; une catégorie passe en rouge si elle dépasse.
- **Épargne de la semaine** (ex. 100 €) : une case à cocher, dès qu'elle est cochée c'est considéré comme fait.
- Ajouter une dépense : montant, catégorie, description facultative, date. Toucher une dépense pour la modifier ou la supprimer.
- Les semaines vont du lundi au dimanche ; flèches pour revoir les semaines passées.
- **Deux vues** (onglets *Semaine* / *Mois*) :
  - *Semaine* : le détail de la semaine, catégorie par catégorie.
  - *Mois* : un grand bloc avec le total dépensé du mois et le total mis de côté, le total par catégorie,
    puis chaque semaine en menu déroulant (catégories, case épargne, dépenses).
    Une semaine compte dans le mois où tombe son lundi.
- Réglages (bouton en haut à droite) : limites, noms et emojis des catégories, montant d'épargne, sauvegarde / restauration.
- S'installe sur l'écran d'accueil de l'iPhone de la même façon (ouvrir l'URL `/budget/` dans Safari).
