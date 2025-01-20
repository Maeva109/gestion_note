# Projet de Gestion des Notes

## Fonctionnalités
- Enregistrer une matière
- Enregistrer un apprenant
- Enregistrer une note pour un apprenant
- Afficher les matières, les apprenants, et les notes d’un apprenant

## Structure des Classes
### Classe Matiere
- Attributs : nom, code ... 
- Méthodes :
  - ajouterMatiere(matieres, nom, code ... )
  - afficherMatieres(matieres ... )

### Classe Apprenant
- Attributs : nom, prenom, id ....
- Méthodes :
  - ajouterApprenant(apprenants, nom, prenom, id ...)
  - afficherApprenants(apprenants   ... )

### Classe Note
- Attributs : valeur, apprenantId, matiereCode ...
- Méthodes :
  - ajouterNote(notes, valeur, apprenantId, matiereCode ...)
  - afficherNotesApprenant(notes, apprenantId ...)