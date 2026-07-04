<p align="center">
  <img src="https://i.postimg.cc/44jFBZ2K/discord-logo.webp" alt="DisRpCord Logo" width="120"/>
</p>

<h1 align="center">DisRpCord</h1>

<p align="center">
  Rich Presence Discord personnalisée — exécutables Windows & Android.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-active-brightgreen" alt="status"/>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20Android-0078D6" alt="platforms"/>
</p>

---

## 📖 À propos

**DisRpCord** permet d'afficher une **Rich Presence personnalisée** sur Discord (jeu, activité custom, images, boutons, chrono en temps réel...).

> 📦 Ce dépôt sert uniquement de stockage pour les builds (`.exe` / `.apk`). Ce n'est pas un projet open-source.

## 📥 Téléchargements

| Plateforme | Fichier | Lien |
|---|---|---|
| Windows | `DisRpCord.exe` | [Releases](https://github.com/ClmentCch/DisRpCord/releases) |
| Android | `DisRpCord.apk` | [Releases](https://github.com/ClmentCch/DisRpCord/releases) |

## 🚀 Utilisation

**Windows**
1. Télécharge `DisRpCord.exe`
2. Lance Discord
3. Double-clique sur l'exécutable
4. Ta Rich Presence s'affiche sur ton profil tant que l'app tourne

**Android**
1. Télécharge `DisRpCord.apk`
2. Autorise l'installation depuis une source inconnue si demandé
3. Installe et lance l'application

> ⚠️ Windows SmartScreen ou Android peuvent afficher un avertissement pour les fichiers non signés. C'est normal pour un build perso.

## ⚙️ Configuration

Le fichier `config.json` (à côté de l'exécutable) contient les infos de la présence :

```json
{
  "clientId": "TON_CLIENT_ID",
  "details": "En train de coder un truc cool",
  "state": "Projet DisRpCord",
  "largeImageKey": "logo",
  "largeImageText": "DisRpCord",
  "startTimestamp": true
}
```

---

<p align="center">Projet perso de Clément</p>
