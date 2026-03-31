# LAB 5 – Convertisseur Température & Distance (Fragments + Onglets)

## 📱 Description du projet
Cette application Android, développée en Java, permet de réaliser deux types de conversions courantes via une interface moderne organisée en onglets :
1.  **Température** : Conversion Celsius ↔ Fahrenheit.
2.  **Distance** : Conversion Kilomètres ↔ Miles.

L'application utilise des composants Android récents comme **TabLayout**, **ViewPager2** et des **Fragments**.

---

## 🚀 Fonctionnalités
- ✅ **Navigation par Onglets** : Passage fluide entre les convertisseurs grâce au ViewPager2.
- ✅ **Conversions bidirectionnelles** : Choix du sens de conversion via des boutons radio.
- ✅ **Validation des saisies** : Message d'alerte (Toast) si le champ est vide.
- ✅ **Menu Quitter** : Option disponible dans la barre d'action pour fermer l'application.
- ✅ **Confirmation de fermeture** : Boîte de dialogue de confirmation lors de l'appui sur la touche "Retour" ou le menu "Quitter".

---

## 🛠️ Technologies utilisées
- **Langage** : Java
- **UI Components** : Material Design (TabLayout, FloatingActionButton, AlertDialog)
- **Navigation** : ViewPager2 + FragmentStateAdapter
- **Minimum SDK** : API 24 (Android 7.0)

---

## 📂 Structure du projet
- `MainActivity.java` : Gère le TabLayout et la logique de sortie.
- `ViewPagerAdapter.java` : Gère l'affichage des fragments dans le ViewPager2.
- `TempFragment.java` : Logique de conversion des températures.
- `DistanceFragment.java` : Logique de conversion des distances.
- `res/layout/` : Fichiers XML définissant l'interface utilisateur.
- `res/menu/` : Définition du menu d'options.

---

## 📺 Démonstration (Vidéo)
https://github.com/ABDONOKRA/developementmobile-lab5x/issues/1

## ✍️ Auteur
Projet réalisé dans le cadre du cours : **Programmation Mobile : Android avec Java**.
