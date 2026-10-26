# AUDIT.md : à compléter

Pour chaque ligne, retrouve le problème correspondant dans `src/App.tsx` / `src/App.css`
et remplis les 3 colonnes. Il y a **6 problèmes volontaires** dans ce starter.

| # | Problème trouvé (où, quoi) | Principe WCAG (P / O / U / R) | Pourquoi c'est bloquant, et pour qui |
|---|------------------------------|-------------------------------|----------------------------------------|
| 1 |  La balise image, pas alt| Perception | On nous n'avons pas d'alternative pour les personnes qui ne peuvent pas bien voir l'image, ceux qui utilise un lecteur d'écran ou bien lorsque la ressource ne s'affiche pas  |
| 2 | div on click (non type bouton) | Opérable | On ne peut pas les atteindre au clavier|
| 3 | h1 puis h3 | Robuste | mauvaise hiérarchie des titres, emp^che une bonne navigation |
| 4 | nom lien cliquez ici | Compréhensible | Le texte du lien n'est pas défini, on doit pour comprendre un lien sans avoir à être dans le contexte|
| 5 | On ne peut pas mettre en pause le .carousel | Opérable | L'utilisateur doit pouvoir gérer son environnement |
| 6 | dots de couleurs | P | Une information ne doit jamais être véhiculée seulement grâce à la couleur car tout le monde n'est pas en mesure de percevoir les différences (ex: daltonisme) |

> Rappel : P = Perceptible, O = Opérable, U = Utilisable (Compréhensible), R = Robuste.
