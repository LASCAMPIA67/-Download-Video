# 📱 DOWNLOAD – Raccourci iOS  
Créé par **LASCAMPIA67**

DOWNLOAD est un raccourci iOS conçu pour télécharger facilement des vidéos depuis les principales plateformes (Twitter/X, YouTube, Facebook, Instagram, TikTok). Une fois la vidéo récupérée via les services compatibles, elle est automatiquement importée dans Photos, puis le dossier Downloads est nettoyé.

---

## 🔧 Prérequis

### 📲 SnapTik (obligatoire pour TikTok)  
https://apps.apple.com/app/id6461307222

### 🦁 Brave Browser (fortement recommandé)  
https://apps.apple.com/app/id1052879175  
Brave permet une meilleure compatibilité avec les sites de téléchargement, un blocage des traqueurs et un système de téléchargement fiable.

### 🌐 Cloudflare 1.1.1.1 (WARP recommandé)  
https://apps.apple.com/app/id1423538627

#### ⭐ Pourquoi utiliser Cloudflare WARP ?
- Améliore la vitesse de connexion  
- Contourne certains blocages géographiques  
- Chiffrement DNS → meilleure confidentialité  
- Réduit les interférences des FAI  
- Rend les pages de téléchargement plus fiables (SaveFrom, SnapTik, SSSTwitter…)  
- Optimisation du routage réseau pour des téléchargements plus stables  

---

## 🚀 Fonctionnalités du raccourci

- Détection automatique du lien dans le presse-papiers  
- Support de : Twitter/X, YouTube, Facebook, Instagram, TikTok  
- Redirection intelligente vers :  
  - ssstwitter.com  
  - savefrom.net  
  - SnapTik  
- Surveillance automatique du dossier **Downloads**  
- Importation automatique dans Photos  
- Suppression des fichiers après traitement  

---

## 🧠 Fonctionnement interne

1. Analyse de l’URL dans le presse-papiers  
2. Identification de la plateforme  
3. Ouverture du service approprié  
4. Surveillance du dossier Downloads  
5. Importation automatique dans Photos  
6. Nettoyage du dossier  

---

## 🛠️ Importer *toutes* les vidéos (correction obligatoire)

Si seul le dernier fichier se télécharge, voici la solution :  
Remplace :

```
Obtenir Premier élément depuis Contenu du dossier
Enregistrer Élément dans Photos
```

Par :

```
Répéter avec chaque Élément dans
    Contenu du dossier filtré (mp4, mov, m4v)
        Enregistrer Élément dans Photos
Fin du répéter
```

✔ Résultat : toutes les vidéos du dossier sont importées.

---

## 📦 Fichiers du dépôt

| Fichier | Rôle |
|--------|------|
| `DOWNLOAD.shortcut` | Le raccourci complet |
| `README.md` | Documentation principale |
| `VERSION.md` | Historique des mises à jour |
| `PRIVACY.md` | Détails sur la confidentialité |
| `Screenshots/` | Captures du raccourci |

---

## 🔒 Confidentialité

- Aucune donnée n’est collectée  
- Aucun envoi externe imposé (sauf sites de téléchargement choisis)  
- Tout le traitement se fait en local  
- Accès uniquement : presse-papiers, dossier Downloads, Photos  

---

## 👤 Auteur

- Créateur : **LASCAMPIA67**  
- Compatibilité : iOS 26.1+  
- Version : 1.0
"""

