🖥️ Site Collabo - Projet HTML & CSS

📝 Description

**Site Collabo** est un projet collaboratif visant à créer une **landing page statique** pour un **site e-commerce fictif** spécialisé dans la décoration intérieure.

L’objectif principal est double :

1. **Renforcer les compétences en intégration web (HTML & CSS)** sans framework externe.
2. **Maîtriser la collaboration en équipe via Git et GitHub**, avec une organisation professionnelle (branche, pull request, code review).

---

## 👥 Équipe & Responsabilités

| Membre                | GitHub                                                     | Responsabilité                                           |
| --------------------- | ---------------------------------------------------------- | -------------------------------------------------------- |
| **hackusman**         | [@hackusman](https://github.com/hackusman)                 | Structure générale, intégration finale, gestion Git      |
| **John98997615**      | [@John98997615](https://github.com/John98997615)           | Section : **Header**                                     |
| **Corn7nelio**        | [@Corn7nelio](https://github.com/Corn7nelio)               | Section : **Shop Home Must-Haves**                       |
| **cedric-228**        | [@cedric-228](https://github.com/cedric-228)               | Sections : **Smart Solutions** & **Essentials Specials** |
| **sebastienleAKPOTO** | [@sebastienleAKPOTO](https://github.com/sebastienleAKPOTO) | Section : **Find Your Perfect Home Upgrade**             |
| **Amiir22-24**        | [@Amiir22-24](https://github.com/Amiir22-24)               | Section : **Footer**                                     |

---

## 📁 Structure du projet

```
collabo/
│
├── css/
│   └── style.css          # Feuille de style globale
│
├── images/                # Dossier contenant toutes les images
│
├── index.html             # Page principale du site (landing page)
│
└── README.md              # Présentation et instructions du projet
```

---

## 🧱 Structure de `index.html`

Voici la structure de base du fichier `index.html` à respecter **strictement** :

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Site Collabo - Déco Intérieure</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

  <!-- ====== HEADER ====== -->
  <header id="header">
    <!-- John98997615 : intégrer ici -->
  </header>

  <!-- ====== SECTION : Shop Home Must-Haves ====== -->
  <section id="shop-home">
    <!-- Corn7nelio : intégrer ici -->
  </section>

  <!-- ====== SECTION : Smart Solutions For Every Room ====== -->
  <section id="smart-solutions">
    <!-- cedric-228 : intégrer ici -->
  </section>

  <!-- ====== SECTION : What Our Essentials Are Special? ====== -->
  <section id="essentials-specials">
    <!-- cedric-228 : intégrer ici -->
  </section>

  <!-- ====== SECTION : Find Your Perfect Home Upgrade ====== -->
  <section id="perfect-upgrade">
    <!-- sebastienleAKPOTO : intégrer ici -->
  </section>

  <!-- ====== FOOTER ====== -->
  <footer id="footer">
    <!-- Amiir22-24 : intégrer ici -->
  </footer>

</body>
</html>
```

### 🔐 Règles :

* N'ajoutez **aucune autre section** sans concertation.
* Ne touchez pas aux sections des autres.
* Vos **classes CSS** doivent être spécifiques pour éviter les conflits.
* Si besoin d’un `div.wrapper`, utilisez vos propres identifiants ou classes.

---

## 🚀 Instructions de lancement (pour tester localement)

```bash
git clone https://github.com/hackusman/collabo.git
cd collabo
```

Puis ouvrez le fichier `index.html` dans votre navigateur.

---

## 🔄 Processus Git à suivre

### 1. Créez votre branche

```bash
git checkout -b votre-pseudo-nomsection
```

Ex : `git checkout -b john-header`

### 2. Développez votre section uniquement

Ajoutez votre code **dans la bonne balise** du `index.html`, et votre CSS dans `style.css`.

### 3. Poussez vos changements

```bash
git add .
git commit -m "Ajout section Header"
git push origin votre-branche
```

### 4. Créez une Pull Request (PR) vers `main`

L'intégration finale sera validée par **hackusman**.
