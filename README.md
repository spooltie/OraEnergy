# ⚡ Ora Energy

Site vitrine de **Ora Energy**, une marque fictive de boissons énergisantes artisanales et naturelles, à base de gingembre et de romarin, **sans caféine, sans taurine et sans sucre ajouté**.

Le site est réalisé en **HTML / CSS** avec un peu de JavaScript, sans framework ni étape de build.

---

## 📄 Pages

| Page | Fichier | Contenu |
|------|---------|---------|
| Accueil | `index.html` | Bannière « BOOST ton énergie », présentation de la marque, fil d'actualité X (Twitter) |
| Nos Produits | `produits.html` | Les 3 boissons de la gamme, les avantages (« Pourquoi Ora ? ») et les ingrédients |
| Notre Histoire | `histoire.html` | L'équipe fondatrice et la frise chronologique de 2018 à 2026 |
| Contact | `contact.html` | Coordonnées et formulaire de contact |

Chaque page a sa propre feuille de style (`style.css` pour l'accueil, puis `produits.css`, `histoire.css` et `contact.css`).

## 🥤 La gamme

| Boisson | Saveurs | Format |
|---------|---------|--------|
| **Ora Émeraude** | Gingembre, romarin, citron vert | 330 ml · 2,30 € |
| **Ora Ruby** | Gingembre épicé, romarin, citron, fruits rouges | 330 ml · 2,30 € |
| **Ora Améthyste** | Gingembre frais, romarin, menthe, myrtille | 330 ml · 2,30 € |

## ✨ Fonctionnalités

- Barre de navigation commune à toutes les pages
- Barre de progression du défilement (en JavaScript)
- Fil X/Twitter intégré (compte [@EnergyOra](https://twitter.com/EnergyOra))
- Frise chronologique de l'histoire de la marque
- Formulaire de contact (nom, email, sujet, message)
- Mise en page adaptée aux mobiles grâce aux media queries
- Polices personnalisées chargées avec `@font-face`

## 🗂️ Structure du projet

```
OraEnergy/
├── index.html          # Accueil
├── produits.html       # Nos produits
├── histoire.html       # Notre histoire
├── contact.html        # Contact
├── style.css           # Styles de l'accueil
├── produits.css
├── histoire.css
├── contact.css
├── RESSOURCES/         # Logos, canettes, icônes (PNG / WebP)
└── FONTS/              # Polices (New Astro, Lemon Milk, Widescreen)
```

## 🚀 Lancer le site

Aucune installation n'est nécessaire.

```bash
git clone https://github.com/spooltie/OraEnergy.git
cd OraEnergy
```

Ouvrez ensuite `index.html` dans votre navigateur.

Vous pouvez aussi lancer un petit serveur local :

```bash
python3 -m http.server 8000
# puis ouvrez http://localhost:8000
```

> Une connexion internet est nécessaire pour afficher le fil X/Twitter.

## 🎨 Charte graphique

- **Couleurs :** noir `#000000`, gris anthracite `#1F1F1F`, blanc `#FFFFFF` et vert néon `#43F986` / `#00FF88`
- **Polices :** *New Astro* (titres et textes) et *Lemon Milk*
- **Couleurs par produit :** vert pour Émeraude, rouge pour Ruby, violet pour Améthyste

## 🛠️ Technologies

- HTML5
- CSS3 (Flexbox, media queries, `@font-face`)
- JavaScript (barre de progression du défilement)
- Widget X/Twitter

## 📌 Limites actuelles

- Le formulaire de contact n'envoie pas encore les messages : il faudrait le relier à un service comme Formspree ou à un back-end.
- Les boutons « Acheter » ne mènent pas encore à une boutique.
- Les liens *Mentions légales*, *Cookies* et *Confidentialité* ne mènent pas encore à des pages.
- Les polices *Widescreen* présentes dans `FONTS/` sont des versions d'essai (*Trial*) et ne sont pas utilisées par les feuilles de style.

## 👤 Auteur

Réalisé par **[spooltie](https://github.com/spooltie)**.

---

*Ora Energy est une marque fictive créée pour ce projet.*
