[Recette du Lomo Saltado](https://github.com/NicolasJamar/exercice-markdown/blob/master/lomo.md)

# exercice-markdown

## Introduction

Ce document est un mémo concernant le markdown et un inventaire de sa syntaxe.
J'ai également ajouté un lien sur la recette du Lomo Saltado. 

## Markdown : définition

Markdown est un système d’édition et de formatage de texte ; c’est à la fois une syntaxe, un script de conversion texte → HTML et un format de fichier. Il est couramment utilisé pour les fichiers de documentation d’un projet ou d’un jeu de données -souvent nommé readme.md. Il est stocké au format texte classique.

La philosophie du système veut que le texte écrit soit lisible sans interpréteur particulier en mode texte. Il est léger et épuré de l’essentiel de la verbosité d’un language balisé. Les éléments de syntaxe sont des caractères de ponctuation qui font sens visuellement même non convertis. Une fois converti, le navigateur web (qui joue alors le rôle d’interpréteur) en rendra la lecture plus claire.

Les fichiers sont généralement enregistrés avec l’extension .md (ou .markdown )

source : [Un guide pour bien commencer avec Markdown](https://blog.wax-o.com/2014/04/tutoriel-un-guide-pour-bien-commencer-avec-markdown/)

## La liste à puces

*Pour créer une liste à puces, procédez de la manière suivante*

 * Ecrivez un astérisque 
 * Ecrivez votre texte
 * Faites la même chose à la ligne suivante

## La liste numérotée

*Pour créer une liste numérotée, procédez de la manière suivante*

  1. Mettez un chiffre
  2. Mettez un point
  3. Mettez votre texte
  4. Répétez les 3 points précédents avec la suite logique du chiffre
  
  ## Les Titres
  
  ### Ici un titre de niveau 3
   #### Ici un titre de niveau 4
  
  ## Les liens
   
   [Lien vers la page Wikipédia de Markdown](https://fr.wikipedia.org/wiki/Markdown)
  
    [texte du lien](url_du_lien "texte pour le titre, facultatif")

 ## Image statique
  
  ![Logo de markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png)
  
    ![Texte alternatif](url_de_l'image "texte pour le titre, facultatif")
    
  ## Image animée
  
  ![Des crayons qui tournent](https://cdn.dribbble.com/users/46315/screenshots/1065283/icons-animation.gif) 
  
 ## Liste à puces imbriquées
  *Pour créer des listes à puces imbriquées, procédez comme suit:*
  
  * Ecrivez un astérisque 
  * Ecrivez votre texte
  * Faites la même chose à la ligne suivante
     * Faire un retrait
     * Créez une nouvelle liste
     * Et ainsi de suite...
  
  ## Coloration syntaxique 
  
   ```javascript
      var s = "JavaScript syntax highlighting";
      alert(s);
   ```

   


