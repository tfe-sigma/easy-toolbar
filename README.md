easy-toolbar
============
This module adds a toolbar component that can be added on every page of your site.

    The toolbar gives access to the following:  
    Send page per email Print page
    Generate a PDF export of the page
    Generate an epub export (ebook) of the page
    Translate the page (links to Google translate)   


The toolbar uses the flying-saucer-pdf API to generate the PDF and calibre-ebook for epub. 

Known limitation: the PDF generator is based on strict XHTML. Your source has to be valid, especially not to contain HTML entities, although we automatically convert most of them

============
How to install

    Install the software caliber-ebook (http://calibre-ebook.com/)          
         
    Before you deploy the module, you have to update the first lines of the file ModuleSigmaToolbar.properties and fill the temp directory for epub generation, and the command paths for the ebook-convert program    
              
    Deploy the module on your Jahia server                

    Add the component “toolbar” on every page of the site  

========================================================================

Ce module permet d'ajouter une barre d'outils sur les pages de votre site.

La barre d'outils dispose de ces fonctionnalités :               

         Envoyer la page par email               
         Imprimer la page              
         Générer un PDF de la page             
         Générer un epub de la page              
         Traduire la page (lien google translate) 


La barre d'outils utilise l'API flying-saucer-pdf pour la génération de PDF et calibre-ebook pour générer les epub.

La générateur de PDF requière des pages en strict XHTML et ne pas contenir de HTML entities.

-----------------------------------------------
Comment installer : 

    Installer le logiciel calibre-ebook  (http://calibre-ebook.com/)

    Avant le déploiement du module, vous devez mettre à jour les premières lignes du fichier ModuleSigmaToolbar.properties en y renseignant le répertoire temporaire pour la génération des epubs, ainsi que les commandes pour executer le programme ebook-convert.

    Deployer le module sur votre serveur Jahia.

    Ajouter le composant toolbar sur la page du site.
