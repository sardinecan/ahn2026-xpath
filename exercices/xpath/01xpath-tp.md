# TP XPath

Effectuez les requêtes suivantes sur le fichier `will_AN_0440.xml`

## Chemins simples
1. Écrire le chemin absolu vers le nœud *racine* du document, vers le nœud *text* et vers le nœud *sourceDesc*
2. Une fois dans le nœud *sourceDesc*, écrire le chemin relatif (sans partir de la racine donc…) vers le nom du manuscrit

## Jokers et opérateurs
3. Sélectionnez tous les nœuds *persName*, quel que soit leur emplacement dans le document
4. Sélectionnez à la fois tous les nœuds *lb* et tous les nœuds *pb*
5. Sélectionnez tous les *sic* descendant d'un *choice* n'importe où dans le document

## Prédicats
6. Sélectionnez le premier nœud (peu importe son type) descendant de l'élément *TEI*
7. Sélectionnez uniquement les sauts de ligne avec un attribut *break*
8. Sélectionnez les *placeName* de valeur *'Paris'*
9. Sélectionnez les *paragraphes* ayant un descendant *placeName* de valeur *'Paris'*
10. Sélectionnez tous les nœuds comportant un attribut *type*
11. Sélectionnez tous les nœuds comportant un attribut *type* ou un *xml:id*
12. Sélectionnez tous les nœuds comportant un attribut *type* et un *xml:id*
13. Sélectionnez tous les *placeName* possédant un attribut *type* de valeur 'willPlace' ou de valeur 'otherPlace'

## Syntaxe non abrégée
14. Sélectionnez le nœud parent de tous les nœuds comportant un attribut *type*
15. Sélectionnez tous les *éléments frères* **suivant** le *premier paragraphe* de la *div*

## Comparaisons et fonctions sur les nœuds
16. Sélectionnez tous les noms de lieu dont le type n'est pas 'willPlace'
17. Récupérez les éléments *date*, dont l'attribut *when* commence par « 1914 »
18. Sélectionnez les nœuds dont la position est supérieure à 2
19. Sélectionnez tous les *éléments enfants* de *TEI* dont la *position est supérieure à 1*

## Question (très) avancée
20. Sélectionnez le dernier nœud *date* dans l'ordre du document (i.e. un nœud date, tel qu'il n'ait pas de successeur du même type dans l'ordre du document)