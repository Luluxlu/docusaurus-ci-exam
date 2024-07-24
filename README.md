# Docusaurus Exam

## 1 - Créer un repo Git

## 2 - Initialisation de Docusaurus

### Créer le site Docusaurus avec la commande :

npx create-docusaurus@latest my-website classic

### Pour lancer le site faite la commande : 

cd my-website
npx docusaurus start

### Push le site sur Github avec la commande : 

git add. 

git commit -m "add docusaurus"

git push

### Créer une nouvelle branch appeler gh-pages

### Aller sur Github dans l'onglet setting, puis Pages

### Choisir la branch gh-pages comme source de déployment

### Créer un fichier deploy yaml avec la config pour build le site à chaque push, bien mettre ce fichier dans un dossier .github/workflows à la racine du projet

### commit et push le projet pour compliler le site sur Github

### Faire attention d'avoir au préalable créer un tokken d'acces au projet et une variable secret action pour avoir les droits sur le projet 



