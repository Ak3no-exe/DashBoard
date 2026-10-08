# Mon Dashboard (APK)

Dashboard tout-en-un (TikTok, météo, actus, agenda, révisions) empaqueté en app Android avec Capacitor.

## Compiler l'APK avec GitHub
1. Crée un dépôt GitHub vide et envoie-y **tout** le contenu de ce dossier, y compris le dossier caché `.github`.
   Si l'envoi par le site ne prend pas `.github`, clique sur « Add file > Create new file », tape
   `.github/workflows/build-apk.yml` comme nom et colle le contenu du fichier fourni.
2. Va dans l'onglet **Actions**. Le build démarre tout seul à chaque envoi sur `main`
   (ou lance « Build APK » avec « Run workflow »).
3. Quand il est vert (3 à 6 minutes), ouvre l'exécution et télécharge **mon-dashboard-apk** en bas de page (un zip contenant `app-debug.apk`).
4. Envoie l'APK sur ton téléphone, ouvre-le et autorise l'installation depuis cette source.

## Hors connexion
- Tes données (TikTok, agenda, cartes) sont enregistrées dans l'app et marchent sans internet.
- Météo, actus et taux de change ont besoin d'internet. Sans connexion, l'app affiche la dernière réponse reçue.

## Modifier l'app
Change `www/index.html`, envoie sur GitHub, et un nouvel APK est construit.
