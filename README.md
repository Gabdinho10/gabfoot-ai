# GABFOOT AI — prototype Flutter

Ce dossier contient le premier prototype de l'interface Android GABFOOT AI.

## Contenu actuel
- Interface sombre noir / bleu électrique
- Navigation Accueil, Live, Compétitions, IA et Favoris
- Cartes de matchs de démonstration
- Écran d'analyse avec probabilités de démonstration

## Important
Les équipes, horaires et pourcentages affichés dans cette version sont fictifs et servent uniquement à présenter l'interface. Aucune donnée sportive réelle n'est encore connectée.

## Pour compiler l'APK
Il faut installer Flutter et Android SDK sur un ordinateur, puis depuis ce dossier exécuter :

```bash
flutter pub get
flutter build apk --release
```

L'APK sera généré dans :
`build/app/outputs/flutter-apk/app-release.apk`

## Prochaine étape
Configurer un fournisseur de données football, protéger la clé API dans un backend, puis connecter les calendriers, scores, statistiques et le moteur de probabilités.
