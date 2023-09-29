# Refonte web : développement 🚀
![cover](./cover.PNG)

> ## Introduction :

> ### Les caractéristiques Positives pour ce Site Web

> #### Accessibilité :
> (Avec l'analyseur Lighthouse :)
>**Point positif :**
> 1. **Ordre Logique des Onglets :** Assurez-vous que l'ordre de tabulation clavier sur votre site est logique et intuitif pour faciliter la navigation.
> 2. **Contrôles Interactifs Accessibles au Clavier :** Tous les éléments interactifs, tels que les boutons et les formulaires, doivent être utilisables via le clavier.

>**Point négatif :**
> 1. Aucune balise ```<meta name="viewport">``` n'a été trouvée.

#### SEO (Optimisation pour les moteurs de recherche) :
>**Point positif :**
> 1. La page a un code de statut HTTP réussi.
> 2. Les liens ont un texte descriptif.
> 3. Les liens sont explorables.
> 4. La page n'est pas bloquée de l'indexation.
> 5. Le document a une balise hreflang valide.

>**Point négatif :**
> 1. Le document n'a pas de méta-description.
> 2. Le manifeste de l'application web n'est pas configuré et pas présente.

#### Les Meilleures Pratiques :
> **Point positif :**
> 1. Évite de demander la permission de géolocalisation lors du chargement de la page.
> 2. Évite de demander la permission de notifications lors du chargement de la page.
> 3. Permet aux utilisateurs de coller du contenu dans les champs de saisie.
> 4. Affiche les images avec le bon rapport d'aspect.
> 5. Fournit des images avec une résolution appropriée.
> 6. La page a la balise HTML doctype.
> 7. Définit correctement l'encodage des caractères.
> 8. Évite les écouteurs d'événements de déchargement.
> 9. Évite les API obsolètes.
> 10. Aucun problème dans le panneau des problèmes dans les outils de développement Chrome.
> 11. La page comporte des cartes source valides.
> 12. Le document évite les plugins.

>**Point négatif :**  
> 1. Le manifeste de l'application web n'est pas configuré et pas présente.


Ces caractéristiques positives reflètent l'effort mis dans la réalisation de ce site web pour assurer une expérience utilisateur optimale, une accessibilité accrue, et une meilleure visibilité sur les moteurs de recherche malgré l'abscence du fichier de site web manifest et le fait que l'entête ne sois pas complète  
(manque de la balise **meta view-port**, des balises "**link rel** pour les icons ou encore le la balise **meta http-equiv="X-UA-Compatible" content="IE=edge"**. )  

>Plus globalement, on peut voir au sein du code HTML que l'identation n'est pas respecté mais aussi que les balises <**div**> sont utilisées parfois à outrance alors que des balises <**section**> seraient plus apréciées,que la Cover du markdown ne se trouvait pas dans asset ,que les balises <**form**> n'était pas présentes , qu'il manquait les "**alt** au sein des liens dans les balises <**a**>.


![AUR license](https://img.shields.io/aur/license/c)