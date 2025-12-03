# 🚨 README – TÂCHES À FAIRE AUJOURD'HUI (03/12/2025) 🚨

**Tout doit être terminé et soumis en Pull Request avant la fin de la journée !**

Merci de travailler sur ces fonctionnalités.  
👉 **IMPORTANT** : Pour **chaque** fonctionnalité, crée une **nouvelle branche**.  
Nom : `feature/nom-de-la-fonctionnalite`  
Ensuite crée un **Pull Request (PR)** puis **ne fusionne surtout pas !**  
➡️ **Tague-moi** pour review (@ton-pseudo), je vérifierai avant de merger.

### 📏 Règles de commit (OBLIGATOIRES)

Utilise **Conventional Commits** à chaque commit :

| Type     | Quand l’utiliser                              | Exemple                                      |
|----------|-----------------------------------------------|----------------------------------------------|
| `feat`   | Nouvelle fonctionnalité                       | `feat: ajout du bouton de recherche`         |
| `fix`    | Correction de bug                             | `fix: correction affichage température négative` |
| `refactor` | Refonte de code sans changement de comportement | `refactor: extraction composant WeatherCard` |
| `style`  | Mise en forme, design, CSS                    | `style: nouveau dégradé et police plus grande` |
| `chore`  | Tâches diverses (config, dépendances…)        | `chore: mise à jour des dépendances`         |



## 🌦️ Améliorations – Application Météo

- [ ] Ajouter un bouton de recherche  
      Permet à l’utilisateur de cliquer sur “Rechercher” au lieu de déclencher la recherche automatiquement.
- [ ] Afficher des suggestions pendant la saisie  
      Exemple : “Pa” → Paris, Panama, Pasadena (3–5 premières suggestions).
- [ ] Afficher une ville par défaut au chargement  
      Ex : Paris, Tokyo ou New York.
- [ ] Ajouter des icônes météo  
      Associer chaque code météo à une icône (soleil, nuage, pluie, orage…).
- [ ] Améliorer le design (style d’une vraie app météo)  
      • Carte plus large  
      • Dégradés modernes  
      • Icônes stylées  
      • Grande fonte pour la température
- [ ] Ajouter plus d’informations météo  
      • Humidité  
      • Ressenti  
      • Heure de lever / coucher de soleil  
      • Prévision sur 3 jours
- [ ] Afficher un état de chargement (loader)  
      Exemple : “Chargement…” avec un petit spinner.
- [ ] Améliorer la gestion des erreurs  
      Messages clairs :  
      • “Ville introuvable”  
      • “Erreur réseau”  
      • “Veuillez taper au moins 3 lettres”
- [ ] Rendre l’application responsive  
      Meilleure expérience sur mobile et tablette.
- [ ] Ajouter un historique des recherches  
      Affiche les dernières villes consultées.
- [ ] Stocker la ville sélectionnée dans le LocalStorage  
      Recharge automatiquement la météo de la dernière ville utilisée.

## 📝 Améliorations – TODO List

- [ ] Ajouter la modification des tâches  
      Éditer le nom de la tâche sans la supprimer.
- [ ] Ajouter une suppression avec confirmation (pas d’alert())  
      Petite popup ou modal moderne.
- [ ] Ajouter une barre de recherche  
      Filtrer les tâches par mot-clé.
- [ ] Ajouter un statut pour chaque tâche  
      Complète / Active / Incomplète
- [ ] Ajouter la priorité de la tâche  
      Basse – Moyenne – Haute
- [ ] Filtrer par priorité  
      Boutons : “Toutes”, “Priorité haute”, “Priorité moyenne”, etc.
- [ ] Ajouter une date d’échéance  
      Afficher les tâches en retard.
- [ ] Ajouter des catégories / tags  
      Ex : Travail, Maison, École.
- [ ] Ajouter un système de tri  
      Par date / Par priorité / Par statut
- [ ] Ajouter le drag & drop  
      Réorganiser les tâches facilement.
- [ ] Améliorer le design général  
      • Espacements  
      • Icônes  
      • Boutons modernes  
      • Animations légères
- [ ] Bouton pour supprimer toutes les tâches complétées  
      Nettoyage rapide.
- [ ] Sauvegarde dans le LocalStorage  
      Garder les tâches après refresh.
- [ ] Ajouter des statistiques  
      Ex : “5 tâches complétées / 12”.
- [ ] Ajouter un mode sombre  
      Basculer entre light & dark mode.
- [ ] Ajouter des sous-tâches  
      Pour les tâches complexes.
- [ ] Ajouter des animations  
      Lors de l’ajout, suppression, modification.

## 🛠️ Workflow de développement (À SUIVRE À LA LETTRE)

1. Créer une branche pour **chaque** fonctionnalité  
   Exemples :  
   - `feature/search-bar`  
   - `feature/suggestions`  
   - `feature/todo-priority`

2. Développer la fonctionnalité sur ta branche

3. Créer un Pull Request (PR)  
   Titre clair → “Ajout : Système de priorité pour TODO list”

4. **Ne fusionne jamais toi-même**  
   ❌ Pas de merge automatique  
   ❌ Pas de merge sans review

5. **Tague-moi dans le PR**  
   Je relis, corrige si besoin, et je merge moi-même.

**Objectif : Tous les PR créés et tagués avant ce soir !**  
On avance à fond aujourd’hui 💪