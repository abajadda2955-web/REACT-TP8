# TP - Consommer une API avec React

## 🎯 Objectifs

- Comprendre la différence entre `fetch()` et `axios`
- Charger des données depuis une API REST
- Afficher des listes dynamiques dans React
- Gérer les états de chargement et d'erreur
- Structurer proprement son code
---

## Structure du projet
text

tp-api/
├── src/
│   ├── App.js           # Composant principal
│   ├── App.css          # Styles modernes
│   ├── FetchData.js     # Composant avec fetch()
│   ├── AxiosData.js     # Composant avec axios
│   └── index.js         # Point d'entrée
└── package.json

---

## Composants
Composant	   |     Description	API utilisée
=============|=========================================================================
FetchData.js |    Utilise fetch() pour récupérer des articles	JSONPlaceholder /posts   |
AxiosData.js |    Utilise axios pour récupérer des utilisateurs	JSONPlaceholder /users |

---
##Fonctionnalités

✅ Gestion des états

    Chargement : Affichage d'un spinner pendant la requête

    Erreur : Message d'erreur avec bouton de réessai

    Succès : Affichage des données formatées

✅ Fonctionnalités incluses

    Affichage des 10 premiers articles

    Affichage des utilisateurs (nom, email, ville)

    Bouton "Recharger" pour rafraîchir les données

    Statistiques (nombre d'éléments affichés)

    Design responsive et moderne
    
<img width="1070" height="639" alt="image" src="https://github.com/user-attachments/assets/63acdf1e-4f9c-4586-adda-285bdb80a351" />
















