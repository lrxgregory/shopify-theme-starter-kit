# Shopify Theme Starter Kit

This starter kit provides a solid foundation for developing custom Shopify themes. It includes an optimized file structure and essential configurations to quickly start a new project.

## 🚀 Project Structure

```
mon-theme/
├── assets/           # Fichiers statiques (CSS, JS, images)
├── config/           # Fichiers de configuration
│   ├── settings_schema.json  # Définition des paramètres du thème
│   └── settings_data.json    # Valeurs par défaut des paramètres
├── layout/           # Layouts principaux
│   └── theme.liquid  # Template principal du thème
├── locales/         # Fichiers de traduction
│   └── fr.json      # Exemple de fichier de traduction en français
├── sections/         # Sections modulaires
│   └── header.liquid  # Exemple de section pour l'en-tête
├── snippets/         # Snippets réutilisables
│   └── logo.liquid    # Exemple de snippet pour le logo
├── templates/        # Templates spécifiques aux pages
│   ├── home.liquid    # Template pour la page d'accueil
│   └── product.liquid # Template pour les pages de produits
└── vendor/           # Extensions de thème
    └── example.rb     # Exemple d'extension de thème en Ruby
```

## 📝 Component Description

### Assets

Contains all static files required for the theme:

- CSS files for styling
- JavaScript files for interactivity
- Images and other media

### Config

- `settings_schema.json`: Defines the structure of customizable theme settings in the Shopify admin interface
- `settings_data.json`: Stores the default values for theme settings

### Layout

- `theme.liquid`: The main template that defines the overall structure of all site pages

### Locales

Contains translation files for multilingual theme support

### Sections

Modular and reusable components that can be added and configured via the Shopify theme editor

### Snippets

Reusable code fragments that can be included in different parts of the theme

### Templates

Specific templates for different page types:

- Homepage
- Product pages
- Collection pages
- etc.

## 🛠 Installation

1. Clone this repository
2. Install the [Shopify CLI](https://shopify.dev/themes/tools/cli)
3. Log in to your Shopify store
4. Use the following command to start development:
   ```bash
   shopify theme dev --store myshopifystore.myshopify.com
   ```

# FR - Shopify Theme Starter Kit

Ce starter kit fournit une base solide pour développer des thèmes Shopify personnalisés. Il inclut une structure de fichiers optimisée et les configurations essentielles pour démarrer rapidement un nouveau projet.

## 🚀 Structure du Projet

```
mon-theme/
├── assets/           # Fichiers statiques (CSS, JS, images)
├── config/           # Fichiers de configuration
│   ├── settings_schema.json  # Définition des paramètres du thème
│   └── settings_data.json    # Valeurs par défaut des paramètres
├── layout/           # Layouts principaux
│   └── theme.liquid  # Template principal du thème
├── locales/         # Fichiers de traduction
├── sections/        # Sections réutilisables du thème
├── snippets/        # Fragments de code réutilisables
└── templates/       # Templates des pages principales
```

## 📝 Description des Composants

### Assets

Contient tous les fichiers statiques nécessaires au thème :

- Fichiers CSS pour le style
- Fichiers JavaScript pour l'interactivité
- Images et autres médias

### Config

- `settings_schema.json` : Définit la structure des paramètres personnalisables du thème dans l'interface d'administration Shopify
- `settings_data.json` : Stocke les valeurs par défaut des paramètres du thème

### Layout

- `theme.liquid` : Le template principal qui définit la structure globale de toutes les pages du site

### Locales

Contient les fichiers de traduction pour la prise en charge multilingue du thème

### Sections

Composants modulaires et réutilisables qui peuvent être ajoutés et configurés via l'éditeur de thème Shopify

### Snippets

Fragments de code réutilisables qui peuvent être inclus dans différentes parties du thème

### Templates

Templates spécifiques pour les différents types de pages :

- Page d'accueil
- Pages de produits
- Pages de collection
- etc.

## 🛠 Installation

1. Clonez ce repository
2. Installez le [Shopify CLI](https://shopify.dev/themes/tools/cli)
3. Connectez-vous à votre boutique Shopify
4. Utilisez la commande suivante pour démarrer le développement :
   ```bash
   shopify theme dev --store maboutiqueshopify.myshopify.com
   ```

## 💡 Personnalisation

1. Modifiez les fichiers dans le dossier `config` pour définir les options personnalisables de votre thème
2. Ajoutez vos styles personnalisés dans le dossier `assets`
3. Créez ou modifiez les sections dans le dossier `sections`
4. Personnalisez les templates selon vos besoins

## 📚 Documentation Utile

- [Documentation Shopify Liquid](https://shopify.dev/api/liquid)
- [Guide du développement de thèmes](https://shopify.dev/themes)
- [Référence de l'API Shopify](https://shopify.dev/api)
