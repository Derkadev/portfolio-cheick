# TCO — Portfolio Professionnel BTP
### Traore Cheick Oumar | Construction · Architecture · Travaux Publics

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## Aperçu

Portfolio one-page professionnel pour **Traore Cheick Oumar (TCO)**, expert BTP basé à Abidjan, Côte d'Ivoire. Design anthracite & or, entièrement responsive, avec formulaire de contact fonctionnel.

---

## Structure du projet

```
tco-portfolio/
├── index.html          # Page principale (HTML + CSS + JS intégrés)
├── README.md           # Ce fichier
└──assets/img/
    ├── about.jpg       # Photo section À propos
    ├── projet1.jpg     # Villa R+2 Cocody
    ├── projet2.jpg     # Immeuble bureaux Plateau
    ├── projet3.jpg     # Voirie Yopougon
    ├── projet4.jpg     # École Abobo
    ├── projet5.jpg     # Réhabilitation entrepôt
    └── projet6.jpg     # Plan de masse résidence
```

---

## Fonctionnalités

- Loader animé TCO au démarrage
- Navigation sticky avec effet blur au scroll
- Barre de progression de lecture
- Sections : Hero · Services · À propos · Projets · Méthode · Devis
- Compteurs animés (expérience, projets, satisfaction)
- Révélation des éléments au scroll (IntersectionObserver)
- Formulaire de devis avec validation JS en temps réel
- Envoi des messages par email via Web3Forms
- Bouton retour en haut
- Entièrement responsive (mobile, tablette, desktop)

---

## Configuration du formulaire

Le formulaire utilise **[Web3Forms](https://web3forms.com)** — service gratuit, sans backend.

### Étapes :

1. Aller sur [web3forms.com](https://web3forms.com)
2. Entrer l'adresse email de TCO → cliquer **Create Access Key**
3. Copier la clé générée
4. Dans `index.html`, trouver cette ligne :
   ```html
   <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY" />
   ```
5. Remplacer `YOUR_ACCESS_KEY` par la vraie clé

Les messages arriveront directement dans la boîte email renseignée.

---

## Mise en ligne — GitHub Pages

Voir section ci-dessous pour les étapes complètes.

---

## Personnalisation

| Élément | Emplacement dans index.html |
|---|---|
| Numéro de téléphone | Section `#devis` → `.contact-item` |
| Email de contact | Section `#devis` → `.contact-item` |
| Nombre d'années d'expérience | `data-count="8"` dans `.hero-stats` |
| Nombre de projets | `data-count="45"` dans `.hero-stats` |
| Descriptions des projets | Section `#projets` → `.projet-body` |
| Couleur or | Variable CSS `--gold: #C8A96E` |

---

## Licence

Projet privé — Tous droits réservés © 2025 Traore Cheick Oumar