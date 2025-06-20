# MesPhotos

**Stockage web d’images publiques via GitHub** — utile pour héberger des **logos**, **avatars**, **illustrations pour e-mails**, **icônes**, etc., directement exploitables via l'URL :

-> **https://mesphotos.kylianhouedec.fr**

---

## Objectif

Offrir une solution simple, gratuite et fiable pour héberger des images accessibles publiquement, idéale pour :

- Sites web personnels ou professionnels
- E-mails HTML contenant des images (affichage compatible tous clients : Gmail, Outlook…)
- Applications web ou scripts PHP
- Partage de visuels sans serveur ni base de données

---

## Structure du projet
MesPhotos/  
├── Planit/  
│ └── logo.png # Utilisé dans les e-mails de mon projet "Planit"  
└── README.md  

> Chaque dossier peut correspondre à un projet ou un contexte (ex. : `/Planit/`, `/ProfilePics/`, etc.)

---

## ✅ Avantages

- 🔗 **Accès public immédiat** : toutes les images sont accessibles via des URLs HTTPS stables
- 📬 **Compatible clients mail** : les images s'affichent correctement dans tous les principaux clients e-mail
- 💸 **Gratuit & sans serveur** : hébergement GitHub Pages, aucune configuration FTP ou serveur web
- ♻️ **Centralisation** : toutes tes ressources visuelles au même endroit
- 🔐 **Sécurisé par HTTPS** (via GitHub Pages + nom de domaine personnalisé)
- 🧩 **Facile à intégrer** dans n’importe quelle page HTML, CSS ou email

---

## 🔗 Exemple d'utilisation

### En HTML (site web ou e-mail) :

```html
<img src="https://mesphotos.kylianhouedec.fr/Planit/logo.png" alt="Logo Planit" width="150">
```
---
**Projet libre**
Ce projet est open source et sous licence MIT.
Tu peux le forker, l’adapter ou y contribuer librement.
