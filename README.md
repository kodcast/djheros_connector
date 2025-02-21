# DjHeros Connector - Nicotine+ Plugin

## 📌 Description
**Français** :
DjHeros Connector est un plugin pour [Nicotine+](https://github.com/nicotine-plus/nicotine-plus) qui permet de rechercher et télécharger automatiquement des fichiers audio en fonction d'une liste de critères définis. Il s'intègre au projet [DjHeros](https://github.com/kodcast/DjHeros) pour faciliter la récupération de morceaux.

**English** :
DjHeros Connector is a plugin for [Nicotine+](https://github.com/nicotine-plus/nicotine-plus) that allows you to automatically search and download audio files based on predefined criteria. It integrates with the [DjHeros](https://github.com/kodcast/DjHeros) project to simplify track retrieval.

## 🚀 Fonctionnalités / Features
✅ **Recherche automatique** des fichiers audio correspondants  
✅ **Filtres avancés** sur le format (MP3, FLAC, OGG, OPUS, WAV) et la qualité audio  
✅ **Téléchargement automatique** des fichiers trouvés  
✅ **Exclusion des fichiers privés** contenant `[prive]` dans leur nom  
✅ **Intégration directe avec DjHeros**  

## 🔧 Installation

### 🐧 Sous Linux / On Linux
1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/kodcast/djheros_connector.git
   ```
2. **Copier le plugin** dans le dossier des plugins de Nicotine+ :
   ```bash
   mkdir -p ~/.local/share/nicotine/plugins/
   cp -r djheros_connector ~/.local/share/nicotine/plugins/
   ```
3. **Redémarrer Nicotine+** et activer le plugin dans les paramètres.

### 🖥️ Sous Windows / On Windows
1. **Télécharger le dépôt depuis GitHub**
2. **Copier le plugin** dans le dossier des plugins de Nicotine+ : `%APPDATA%/nicotine/plugins/`
3. **Vérifier la configuration** du plugin (URL JSON, filtres audio)
4. **Lancer Nicotine+ et activer le plugin**

## 🎯 Utilisation / Usage
1️⃣ **Lancer Nicotine+ et activer le plugin**
2️⃣ **Entrer l’URL** où se trouve le fichier `propositions.json`
3️⃣ **Sélectionner le format audio et la qualité souhaitée**
4️⃣ **Cliquer sur Rechercher et Télécharger**

## 🤝 Contribution
**Français :**
Les contributions sont les bienvenues ! Vous pouvez signaler un bug, proposer une amélioration ou envoyer une pull request sur [DjHeros Connector](https://github.com/kodcast/djheros_connector).

**English:**
Contributions are welcome! Feel free to report an issue, suggest an improvement, or submit a pull request on [DjHeros Connector](https://github.com/kodcast/djheros_connector).

## 📜 Licence / License
**Français :**
Distribué sous licence **GNU General Public License v3.0**.

**English:**
Licensed under the **GNU General Public License v3.0**.
