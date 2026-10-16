# ✦ Sall Shop — Espace Invité VIP (Édition Anniversaire)

Expérience privée et prestigieuse pour la célébration de l’anniversaire de **Sall Shop**, le **mercredi 28 octobre 2026 dès 14h30 GMT** à Ouakam, Dakar (après le restaurant nigérien).

---

## 🔑 Code d’accès VIP

> **Code d'invitation :** `Sallshop-aniv-vip`

Ce code permet de déverrouiller l'accès complet :
1. **Détails exclusifs du programme** de la journée (Réception, Animation, Défilé de mode, Photos & Pop-up store, Chill & Rencontres).
2. **Génération et téléchargement immédiat du PDF officiel** d’invitation au format haute fidélité (fond noir, liséré or, typographie Helvetica, QR code de contrôle nominatif).
3. **Inscription automatique** dans la liste des invités confirmés.

---

## ✨ Fonctionnalités clés

- **Zéro dépendance serveur** : la validation du code et la production du PDF avec QR code s'exécutent directement dans le navigateur en moins de 100ms.
- **Téléchargement PDF haute résolution** : propulsé par `pdf-lib` et `qrcode`, respectant la charte graphique de luxe Sall Shop.
- **Liste des invités en direct** : affichage actualisé des invités et pseudos confirmés avec persistance locale (`localStorage`).
- **Compte à rebours précis** : synchronisé sur le 28 octobre 2026 à 14h30 GMT.
- **Export calendrier (.ics)** : ajout automatique de l’événement dans Google Agenda, Apple Calendar ou Outlook.
- **Itinéraire & Contacts** : lien Google Maps vers Ouakam, appel direct (`+221 78 582 84 17`) et Instagram officiel (`@sall_shop24`).
- **Vérification d’authenticité** : bandeau de validation instantané via paramètre d’URL `?invitation=...`.

---

## 🚀 Lancement local

```bash
# Installation des dépendances
pnpm install
# ou npm install

# Démarrage du serveur de développement
pnpm dev
# ou npm run dev
```

---

## 📦 Déploiement

Cette application est une SPA moderne standard (React + Vite + Tailwind CSS + TypeScript). Elle peut être déployée en 1 clic sur :
- **Vercel** (`vercel`)
- **Netlify** (`netlify deploy --prod --dir=dist`)
- **GitHub Pages**
- **Cloudflare Pages**
