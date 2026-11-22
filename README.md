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

# Listes 🧳 (dossier `listes/`)

Seconde web-app, indépendante, pour les listes réutilisables : valises, courses, sorties…
Design inspiré de l'app Rappels d'iOS.

- **Mes listes** : chaque liste a un nom, une couleur et un emoji, avec son avancement (« 3/12 », « Prête ✓ »).
- **Chapitres** dans une liste (ex. *Repas* : bavoir, biberon, lait · *Dodo* : gigoteuse, doudou), repliables, avec leur compteur.
- Toucher une ligne pour la **cocher** ; ajout rapide en bas de chaque chapitre (Entrée pour enchaîner).
- **Réinitialiser** (bouton ↺ ou bandeau « Tout est prêt ! ») : tout est décoché pour la prochaine fois, avec « Annuler » au cas où.
- **Modifier** : renommer, supprimer et réordonner éléments et chapitres.
- Menu ⋯ : infos de la liste, masquer les éléments cochés, dupliquer, supprimer ; sur l'accueil : réorganiser, sauvegarder / restaurer (JSON).

Installation : même principe que ci-dessus, avec l'URL `https://<utilisateur>.github.io/Tracker-/listes/`
ouverte dans Safari → **Partager** → **Sur l'écran d'accueil**.
