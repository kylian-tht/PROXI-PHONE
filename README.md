# 📱 PROXI-PHONE Vitré — Site Web Officiel

> **Site vitrine & plateforme de conversion pour l'atelier de réparation de smartphones, tablettes et ordinateurs à Vitré (35500).**

---

## 📌 Présentation du Projet

**PROXI-PHONE** est un atelier indépendant spécialisé dans la réparation express d'appareils mobiles et le dépannage informatique, situé en plein cœur du centre historique de Vitré (**26 Rue de la Poterie, 35500 Vitré**).

Ce site web a été conçu avec une approche **Mobile-First**, ultra-performante et optimisée pour la conversion locale. Il offre aux clients une expérience fluide pour consulter les tarifs, connaître les pannes prises en charge, vérifier la disponibilité des accessoires et demander un devis gratuit en ligne.

---

## 🚀 Caractéristiques & Fonctionnalités Clés

### 1. 🕒 Statut & Horaires en Temps Réel
* **Calculateur automatique d'ouverture** : le statut s'actualise en direct dans l'en-tête et les fiches de contact (*« Ouvert • Ferme à 18h00 »*, *« Fermé • Ouvre demain à 10h00 »*, etc.).
* **Prise en compte des créneaux doubles** (10h-13h / 15h-18h) et de la nocturne du vendredi (fermeture à 19h).
* **Mise en valeur du jour actuel** : la ligne du jour est automatiquement surlignée dans les tableaux d'horaires de chaque page.

### 2. 📲 Expérience Utilisateur & Navigation Mobile
* **Menu déroulant tactile** : navigation principale avec sous-menus thématiques clairs (*Accueil*, *Services*, *Boutique*).
* **Barre d'action fixe mobile (Sticky CTA)** : accès instantané en 1 clic pour téléphoner directement à l'atelier (`06 37 98 13 88`) ou lancer l'itinéraire GPS Google Maps.
* **100% Responsive & Zéro débordement** : structure testée et validée sur toutes les résolutions mobiles (de 320 px à plus de 1920 px) avec défilement vertical fluide sans dérive latérale.
* **Bouton de retour en haut** discret et accessible.

### 3. 🎨 Identité Visuelle & Iconographie Sur-Mesure
* **Charte graphique professionnelle** : alliance du Bleu Royal (`#0d47a1`, `#082b66`) et d'un Jaune Ambré chaleureux (`#f59e0b`).
* **Intégration du logo officiel** en plusieurs déclinaisons adaptées aux formats d'écrans (compact pour header, haute lisibilité pour le footer et badges d'atelier).
* **Palette de pictogrammes personnalisés (1:1)** : 60 pictogrammes carrés haute définition intégrés sans aucune bande blanche pour illustrer chaque type de panne et d'accessoire.

### 4. 📝 Devis Gratuit & Interactif
* Formulaire de demande de devis dynamique ([devis.html](devis.html)).
* Sélecteur visuel d'équipements (*Smartphone*, *Tablette / iPad*, *PC Portable*, *PC Fixe / Mac*).
* Liste déroulante des pannes fréquentes et champs de contact avec validation immédiate côté client.
* Encart direct avec numéro de téléphone pour les urgences.

### 5. 🔍 Référencement Naturel & SEO Local
* **Microdonnées Schema.org (JSON-LD)** configurées pour Google (type `LocalBusiness`, adresse physique, géolocalisation, plage d'horaires complète).
* Balises Open Graph & Twitter Cards pour un partage optimal sur les réseaux sociaux.
* Structure sémantique HTML5 soignée (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).

---

## 📂 Structure des Pages

| Page | Fichier | Description |
| :--- | :--- | :--- |
| **Accueil** | [`index.html`](index.html) | Vue d'ensemble, pannes courantes, garanties atelier, aperçu des accessoires, avis clients Google et plan d'accès. |
| **Services & Réparations** | [`services.html`](services.html) | Détail des interventions : écrans, batteries, connecteurs, désoxydation, microsoudure, tablettes et maintenance PC/Mac. |
| **Boutique & Accessoires** | [`accessoires.html`](accessoires.html) | Gammes disponibles immédiatement en rayon (films hydrogel découpés sur-mesure avec pose offerte, coques antichoc, câbles, chargeurs, supports). |
| **Tarifs & Devis** | [`devis.html`](devis.html) | Formulaire interactif de demande de devis en ligne et rappel des engagements qualité. |
| **Contact & Accès** | [`contact.html`](contact.html) | Coordonnées directes, horaires détaillés, plan interactif Google Maps et formulaire de message. |

---

## 📁 Arborescence du Projet

```text
site web Proxi_Phone/V1 la meilleur/
├── index.html                  # Page d'accueil principale
├── services.html               # Page des prestations de réparation
├── accessoires.html            # Page boutique et protections
├── devis.html                  # Formulaire de devis en ligne
├── contact.html                # Informations d'accès et horaires
├── README.md                   # Documentation du projet
│
└── assets/
    ├── css/
    │   └── style.css           # Feuille de style unique et responsive (Vanilla CSS)
    ├── js/
    │   └── main.js             # Logique applicative (horaires en direct, menu mobile, devis)
    ├── logo/                   # Déclinaisons officielles du logo PROXI-PHONE
    │   ├── logo-compact-horizontal.png
    │   ├── logo-icone-engrenage.png
    │   └── ...
    └── pictogrammes/           # Pictogrammes thématiques au format carré 1:1
        ├── picto-ecran-casse.png
        ├── picto-batterie.png
        ├── picto-film-hydrogel.png
        ├── picto-coque-antichoc.png
        └── ...
```

---

## 🛠️ Technologies Utilisées

* **HTML5 Sémantique** : balisage moderne, accessible et optimisé SEO.
* **CSS3 Vanilla** :
  * Variables CSS (`:root`) pour une gestion centralisée de la charte.
  * Flexbox & CSS Grid adaptatifs.
  * Transitions matérielles douces et animations d'interaction.
  * Zéro framework externe (aucun Bootstrap ou Tailwind nécessaire, garantissant légèreté et contrôle total).
* **JavaScript ES6+ (Vanilla JS)** :
  * Horloge dynamique de calcul des plages d'ouverture hebdomadaires.
  * Gestion du menu burger mobile accessible (`aria-expanded`).
  * Traitement et simulation d'envoi du formulaire de devis.

---

## 💡 Hébergement & Déploiement

Le projet ne nécessitant aucun backend complexe ou base de données pour fonctionner en vitrine, il peut être hébergé instantanément sur n'importe quel hébergeur web ou plateforme statique :

* **Hébergeur standard** : OVH, Hostinger, O2Switch (par simple dépôt FTP dans le dossier `public_html` ou `www`).
* **Hébergement moderne / Jamstack** : GitHub Pages, Netlify, Vercel ou Cloudflare Pages.

---

## 📞 Informations du Magasin

* **Enseigne** : PROXI-PHONE
* **Adresse** : 26 Rue de la Poterie, 35500 Vitré
* **Téléphone direct** : [06 37 98 13 88](tel:0637981388)
* **Horaires d'ouverture** :
  * Mardi à Samedi : 10h00 – 13h00 / 15h00 – 18h00 *(Vendredi jusqu'à 19h00)*
  * Lundi & Dimanche : Fermé
