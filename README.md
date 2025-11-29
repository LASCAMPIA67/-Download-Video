# 📱 DOWNLOAD – Raccourci iOS

Un raccourci intelligent permettant de télécharger rapidement des vidéos depuis plusieurs plateformes (Twitter/X, YouTube, Facebook, Instagram, TikTok) puis d’importer automatiquement les vidéos téléchargées dans l’app Photos.

---

## 🚀 Fonctionnalités

- Détection automatique du lien présent dans le presse-papiers  
- Compatibilité avec :  
  - Twitter / X  
  - YouTube et YouTube Shorts  
  - Facebook  
  - Instagram  
  - TikTok (tiktok.com, vm.tiktok.com, vt.tiktok.com)  
- Redirection vers les plateformes de téléchargement adaptées :  
  - ssstwitter.com  
  - savefrom.net  
  - SnapTik  
- Surveillance du dossier **Downloads**  
- Importation automatique dans l’album Photos  
- Suppression des fichiers téléchargés après traitement  

---

## 🧠 Fonctionnement interne

1. **Analyse du presse-papiers**  
   Le raccourci détecte automatiquement la plateforme en fonction de l’URL copiée.

2. **Ouverture du service adapté**  
   L’URL est ouverte dans le site de téléchargement compatible avec la plateforme détectée.

3. **Surveillance du dossier Downloads**  
   Le raccourci vérifie régulièrement l’arrivée de nouveaux fichiers vidéo (`.mp4`, `.mov`, `.m4v`).

4. **Importation dans Photos**  
   Chaque vidéo détectée est enregistrée dans l’app Photos.

5. **Nettoyage**  
   Le dossier Downloads est vidé après importation pour éviter l’encombrement.

---

## 🛠️ Correction importante : importer *toutes* les vidéos

Par défaut, le raccourci ne récupère que **la dernière vidéo téléchargée**, car il utilise quelque chose du type :

Obtenir Premier élément depuis Contenu du dossier  
Enregistrer Élément dans Photos

Pour importer **toutes** les vidéos téléchargées, remplace cette partie par une boucle :

Répéter avec chaque Élément dans  
    Contenu du dossier filtré (mp4, mov, m4v)  
        Enregistrer Élément dans Photos  
Fin du répéter

✔ Cette modification garantit l’importation de **toutes les vidéos**, pas seulement une.

---

## 📦 Fichiers présents dans ce dépôt

| Fichier | Description |
|--------|-------------|
| `DOWNLOAD.shortcut` | Le raccourci complet |
| `README.md` | Documentation détaillée |
| `VERSION.md` | Historique des mises à jour |
| `PRIVACY.md` | Informations sur la confidentialité |
| `Screenshots/` | Captures d’écran du raccourci (optionnel) |

---

## 🔒 Confidentialité

- Aucune collecte de données  
- Aucun traitement externe en dehors des sites de téléchargement explicitement ouverts  
- Le raccourci n’accède qu’à :  
  - votre presse-papiers  
  - votre dossier Downloads  
  - l’app Photos  
- Le traitement est effectué localement sur votre appareil

---

## 👤 Auteur

- **Compatibilité :** iOS 26.1+  
- **Créateur :** Votre pseudo GitHub  
- **Version :** 1.0  
"""

