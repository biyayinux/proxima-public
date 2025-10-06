
![Logo](https://i.postimg.cc/h4VppyZ0/logo-proxima.png)

# Proxima Public

Mise en place d'une application intelligente 🤖 pour la géolocalisation 📍 du magasin 🏬 le plus proche et la reconnaissance 🔎 des articles 🛒 demandés par le client 👤 en fonction de leur image 🖼️

## METHODOLOGIE

La méthodologie désigne l’ensemble structuré des étapes, techniques et outils mis en œuvre pour conduire un projet de manière rigoureuse, logique et efficace
## Analyse des besoins

Le projet **Proxima** vise à créer une application intelligente capable de **géolocaliser le magasin le plus proche et de reconnaître les articles à partir d’images.**
Les utilisateurs peuvent créer un compte, gérer leur magasin et publier leurs produits classés par catégories.
L’application utilise les **coordonnées GPS** pour localiser les magasins et un **modèle d’IA** pour la reconnaissance visuelle des articles.
Une base de données relationnelle structure les informations sur les utilisateurs, magasins, catégories et articles.
L’objectif final est de **faciliter la recherche de produits locaux et d’améliorer la visibilité des commerçants.**
## Conception / modélisation

#### Modèle Conceptuel de Données (MCD)

![Logo](https://i.imgur.com/1djNGeK.png)

#### Modèle Logique de Données (MLD)

- utilisateurs (id, email, noms, url_image, telephone, lien_facebook, lien_instagram,
lien_tiktok, lien_whatsapp, lien_youtube, dt)
- magasins (id, nom, longitude, latitude, logo, dt, #id_utilisateur)
- categories (id, nom, dt)
- articles (id, nom, prix, devise, photos_json, vector_json, cluster, dt, #id_magasin,
#id_categorie)

#### Dictionnaire de Données
 - [Si vous avez besoin de consulter le dictionnaire de données, veuillez télécharger ce documen](https://github.com/biyayinux/proxima-public/blob/main/MERISE/MCD_MLD.pdf)
 - [Vous pouvez télécharger la structure de la base de données si nécessaire](https://github.com/biyayinux/proxima-public/blob/main/FICHIERS/proxima_db.sql)
 

## Développement / implémentation

Nous avons mis en place une architecture **Microservices avec une base de données partagée**

![Logo](https://i.imgur.com/ybRVQB4.png)

## Pile technologique

### Technologies Backend
[![](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)]()
[![](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)]()
[![](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)]()
[![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)]()
[![](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)]()
[![](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)]()

### Technologies Frontend
[![](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)]()
[![](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)]()
[![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)]()
[![](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)]()
[![](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)]()
[![](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)]()
[![](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)]()

## Profil GitHub des contributeurs

- [@biyayinux](https://github.com/biyayinux)
- [@EJM0101](https://github.com/EJM0101)

## Adresse e-mail des membres de la startup

- exemple1@gmail.com
- exemple2@gmail.com



