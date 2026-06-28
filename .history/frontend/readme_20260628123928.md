## Intégration et gestion Git 

Les branches feature/style et feature/contact ont été intégrées dans main par le membre hernes.

### Processus utilisé :
1. Vérification de main 
2. Fusion de feature/style
3. Fusion de feature/contact
4. Vérification finale de cohérence

### Gestion des conflits :
En cas de conflit Git :
- D'aborb on identifie les zones marquées par <<<<<<< ======= >>>>>>> qui interviennent quand plusieurs personnes modifie la meme partie d'un fichier.
- Ensuite on n'a fusionner les versions des contributeurs.
- Puis supprimer les marqueur identificateurs de plusieurs version.
- ET enfin on effectue un commit de résolution.