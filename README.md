Voici une mise à jour du fichier `README.md` avec un lien vers la documentation associée :

---

# 🍽️ Open Food Fact

Bienvenue dans le projet **Open Food Fact** ! Ce projet utilise l'API Open Food Facts pour récupérer des données alimentaires et alimenter un modèle de prédiction basé sur l'intelligence artificielle. 🎯

---

## 🌟 Fonctionnalités

- 🔍 **Recherche de produits** : Trouvez des informations détaillées sur des produits alimentaires par nom ou code-barres.
- 📊 **Analyse et prédiction** : Les données issues de l’API sont utilisées pour entraîner et tester un modèle de prédiction pour analyser des propriétés alimentaires.
- 🗂️ **Affichage des détails** : Consultez les informations telles que les ingrédients, les valeurs nutritionnelles et les allergènes.

---

## 🔗 Documentation associée

Pour plus d'informations sur l'utilisation de l'API et les fichiers associés, consultez la documentation complète ici :  
👉 [Documentation Simplon Open Food Facts](https://github.com/Simplon-openfoodfacts/documents_other)

---

## 🔧 Prérequis

- 🐍 **Python 3.8 ou supérieur**
- 🌐 **Flask 2.0 ou supérieur**

---

## 🚀 Installation

1. **Cloner le dépôt** :

   ```bash
   git clone https://github.com/Romcro/Open-food-fact.git
   ```

2. **Accéder au répertoire du projet** :

   ```bash
   cd Open-food-fact
   ```

3. **Créer un environnement virtuel** :

   ```bash
   python -m venv venv
   ```

4. **Activer l'environnement virtuel** :

   - Sur **Windows** :
     ```bash
     venv\Scripts\activate
     ```
   - Sur **macOS/Linux** :
     ```bash
     source venv/bin/activate
     ```

5. **Installer les dépendances** :
   ```bash
   pip install -r requirements.txt
   ```

---

## 🛠️ Utilisation

1. **Lancer l'application** :

   ```bash
   flask run
   ```

2. **Accéder à l'application** :
   Ouvrez votre navigateur et rendez-vous sur [http://127.0.0.1:5000](http://127.0.0.1:5000).

---

## 📁 Structure du projet

- 📂 `app/` : Fichiers principaux de l'application Flask.
- 📂 `migrations/` : Gestion des migrations de la base de données.
- 📂 `model/` : Contient le modèle de prédiction basé sur les données alimentaires.
- 📂 `static/` : Fichiers CSS, JavaScript, et images.
- 📂 `templates/` : Modèles HTML pour le rendu des pages.
- 📂 `tests/` : Tests unitaires et d'intégration pour valider l'application.
- 📜 `README.md` : Ce fichier.

---

## 🧠 Intelligence artificielle

L'API Open Food Facts sert de source de données pour entraîner un **modèle de prédiction**.  
Le modèle peut analyser les propriétés nutritionnelles des produits pour :

- Évaluer la qualité nutritionnelle.
- Identifier les allergènes potentiels.
- Prédire des propriétés à partir d'ingrédients ou de compositions nutritionnelles.

L'application utilise des frameworks comme **TensorFlow** et **PyTorch** pour le développement de modèles d'apprentissage automatique. 🔥

---

## 🛡️ Licence

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus d'informations.

---

## 🎉 Remerciements

Merci à [Open Food Facts](https://world.openfoodfacts.org/) pour leur API publique et leur base de données exhaustive, qui rendent ce projet possible. 🙏

---
