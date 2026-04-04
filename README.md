# Mise en application : Création de l'interface avec XAML
**Séance 09** (Le 24/03/2026)

---

### Exercice 01 : Interface simple avec un titre et un bouton
**Objectif :** Créer une fenêtre WPF contenant un titre et un bouton centré.  
**Consignes :**
1. Ajoutez un titre en haut de la fenêtre (utilisez un `Label`).
2. Placez un bouton centré qui affiche un texte indiquant une action à venir.
3. Ajoutez une marge intérieure au bouton pour améliorer l'esthétique.

---

### Exercice 02 : Agencement avec Grid et StackPanel
**Objectif :** Organiser des éléments à l'aide de `Grid` et `StackPanel` pour mieux comprendre la gestion de l'espace.  
**Consignes :**
1. Créez une grille (`Grid`) avec 2 colonnes et 2 lignes.
2. Placez trois boutons empilés verticalement dans la première colonne avec un `StackPanel`.
3. Dans la deuxième colonne, ajoutez un `Label` suivi d'un champ texte (`TextBox`).
4. Ajustez la largeur des colonnes pour que la deuxième colonne prenne tout l'espace disponible.

---

### Exercice 03 : Création d'un formulaire statique
**Objectif :** Créer un formulaire d'inscription en XAML uniquement.  
**Consignes :**
1. Ajoutez les champs suivants :
   - Prénom (`TextBox`)
   - Nom (`TextBox`)
   - Email (`TextBox`)
   - Mot de passe (`PasswordBox`)
2. Ajoutez un bouton « S'inscrire » sous le formulaire.
3. Utilisez une mise en page propre en employant une `Grid` ou un `StackPanel`.

---

### Exercice 04 : Utilisation des ListBox et ComboBox
**Objectif :** Créer une interface où l'utilisateur peut sélectionner des éléments dans des listes déroulantes.  
**Consignes :**
1. Ajoutez une `ComboBox` avec trois choix de pays (ex. France, Canada, USA).
2. Ajoutez une `ListBox` permettant de sélectionner plusieurs centres d'intérêt (ex. Sport, Musique, Lecture).
3. Ajoutez un bouton de validation en bas de l'interface.

---

### Exercice 05 : Création d'une interface avec plusieurs onglets
**Objectif :** Apprendre à structurer une interface avec des onglets (avec `TabControl`).  
**Consignes :**
1. Créez une interface contenant un `TabControl` avec trois onglets :
   - **Accueil** : affiche un message de bienvenue
   - **Formulaire** : réutiliser le formulaire de l'exercice 3
   - **Paramètres** : affiche un champ permettant de modifier la langue
2. Assurez-vous que chaque onglet ait un contenu bien structuré avec des `StackPanel` ou `Grid`.

---

### Exercice 06 : Création d'un menu de navigation
**Objectif :** Créer un menu de navigation horizontal pour simuler une application classique.  
**Consignes :**
1. Ajoutez un `Menu` en haut de la fenêtre avec trois éléments :
   - **Fichier** (avec « Ouvrir » et « Quitter »)
   - **Édition** (avec « Copier », « Coller »)
   - **Aide** (avec « À propos »)
2. Le menu doit être fixé en haut et ne pas être affecté par le redimensionnement de la fenêtre.
3. Ajoutez une zone centrale sous le menu qui affichera le contenu.

---

### Exercice 07 : Interface avec agencement avancé
**Objectif :** Créer une interface avancée combinant `Grid`, `DockPanel`, `Menu`, et `ListView`.  
**Consignes :**
1. Utilisez un `DockPanel` pour organiser l'interface avec :
   - Un `Menu` en haut
   - Une barre latérale à gauche contenant des boutons de navigation
   - Une zone centrale avec un `ListView` affichant des données sous forme de tableau
2. Le `ListView` doit contenir trois colonnes (Nom, Âge, Ville) et quelques données fictives.
3. La fenêtre doit être redimensionnable sans perdre la disposition des éléments.
