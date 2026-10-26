# AUDIT.md : à compléter

Pour chaque ligne, retrouve le problème correspondant dans `src/App.tsx` / `src/App.css`
et remplis les 3 colonnes. Il y a **6 problèmes volontaires** dans ce starter.

| # | Problème trouvé (où, quoi) | Principe WCAG (P / O / U / R) | Pourquoi c'est bloquant, et pour qui |
|---|------------------------------|-------------------------------|----------------------------------------|
| 1 | Bouton "Voir plus" inaccessible | O                          | On ne peut pas atteindre le bouton avec la tabulation, c'est bloquant pour les utilisateurs clavier. |
| 2 | Pas de texte alternatif à la photo | P                       | Le contenu de l'image est inaccessible pour un lecteur d'écran, c'est bloquant pour les personnes mal/non voyantes |
| 3 | Statut des articles indiqué par la couleur seulement | P     | Une personne daltonienne peut ne pas voir la différence, et donc peut ne pas avoir accès à l'information |
| 4 | Saut de h1 à h3 | R                                          | La hiérarchie des titres sert à la navigation d'une page, sauter un niveau casse cette navigation|
| 5 | Bandeau newsletter qui s'affiche sans possibilité de le fermet/mettre en pause| O | Tout contenu doit pouvoir êter maitrisé par l'utilisateur |
| 6 | Liens avec le même texte "cliquez dessus"  | U (ou C) | Le texte des liens n'a pas de sens hors-contexte |

> Rappel : P = Perceptible, O = Opérable, U = Utilisable (Compréhensible), R = Robuste.
