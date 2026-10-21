# Karibotel Domaine Manerinerina

Site vitrine statique du domaine, actuellement présenté comme une version de travail à faire valider.

## Tester en local

Depuis la racine du projet, lancer :

```powershell
python -m http.server 8080 --directory dist
```

Puis ouvrir <http://localhost:8080>. Pour arrêter le serveur, revenir dans le terminal et utiliser `Ctrl+C`.

## Partager la démo avec GitHub Pages

Le workflow `.github/workflows/pages.yml` publie automatiquement le dossier `dist` à chaque push sur `main`.

1. Pousser les fichiers sur le dépôt `karibotel_domaine_manerinerina`.
2. Sur GitHub, ouvrir **Settings → Pages**.
3. Dans **Build and deployment**, sélectionner **GitHub Actions** comme source.
4. Ouvrir l’onglet **Actions** et attendre la fin du workflow **Deploy Karibotel draft to GitHub Pages**.
5. Partager ensuite l’adresse affichée par le workflow, normalement :

   `https://rmvalisoa.github.io/karibotel_domaine_manerinerina/`

Cette adresse est différente de celle du portfolio, car elle utilise le nom de ce dépôt comme chemin.

## Statut de la démo

Le fichier `robots.txt` et la balise `noindex` demandent aux moteurs de recherche de ne pas indexer la démo. GitHub Pages reste toutefois accessible à toute personne qui possède le lien ; ce n’est pas une protection par mot de passe.

## Contenus

Le site utilise les photos et le logo originaux fournis dans `dist/assets`. Les textes s’appuient sur les informations publiques de la page Facebook et de ses relais publics. Les prestations détaillées, capacités et horaires devront être validés avant la mise en ligne définitive.
