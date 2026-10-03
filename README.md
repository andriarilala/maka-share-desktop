# Maka-Share Desktop

L'application de bureau de **Maka-Share** pour les photographes d'événement. Elle trie les photos par visage directement sur l'ordinateur, sans les téléverser, puis prépare les dossiers de livraison et les partage aux clients par un lien protégé par mot de passe.

Ce dépôt héberge uniquement les **installeurs officiels**. Le code source n'y est pas publié.

## Télécharger

| Système | Fichier |
|---|---|
| Windows 10 ou 11, 64 bits | [Maka-Share-Setup.exe](https://github.com/andriarilala/maka-share-desktop/releases/latest/download/Maka-Share-Setup.exe) |
| macOS (Apple Silicon et Intel) | Bientôt disponible |

Toutes les versions sont listées dans les [Releases](https://github.com/andriarilala/maka-share-desktop/releases).

Un compte Maka-Share est nécessaire. Le plan Découverte est gratuit.

## Configuration conseillée

- 8 Go de RAM
- Environ 600 Mo d'espace disque pour l'application, plus le cache des miniatures

## Installation

L'installeur n'est pas encore signé. Au premier lancement, Windows peut afficher « Windows a protégé votre ordinateur » : cliquez sur **Informations complémentaires**, puis **Exécuter quand même**.

Chaque release indique l'empreinte SHA-256 de l'installeur. Pour la comparer sous Windows :

```powershell
Get-FileHash .\Maka-Share-Setup.exe -Algorithm SHA256
```

## Vos photos

- Les photos restent sur votre ordinateur : elles sont lues sur place, jamais copiées ni envoyées pour la reconnaissance faciale.
- Seules les photos d'un dossier que vous choisissez de partager sont envoyées en ligne, sans aucune empreinte de visage.
- Désinstaller l'application ne supprime ni vos photos ni vos données.

## Signaler un problème

Ouvrez une [issue](https://github.com/andriarilala/maka-share-desktop/issues) en précisant la version de l'application et votre système.
