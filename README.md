# TP Relax NG

Compléter le fichier `livres-init.rng` pour qu'il valide le document `livres.xml`.

### Execution : 

* Ouvrir une console à la racine de ce projet.
* lancer `java -jar jing.jar livres-init.rng livres.xml`

**La validation ne doit renvoyer aucune erreur.**

### Test inverse :

* lancer `java -jar jing.jar livres-init.rng livres-invalide.xml`

**Vérifier que des erreurs de validation sont bien levées.**

Le répertoire `solution/` contient un fichier rng valide. (mais d'autres solutions sont possibles...) 
