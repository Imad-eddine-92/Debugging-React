React DevTools permettent d'inspecter et de déboguer des applications React. Elle aide à analyser l'état des composants, les props et le rendu.

On commence par installer l'extension sur notre navigateur (Screenshot 1). Une fois installée, en cliquant sur 'inspecter' et dans la rubrique 'components' on peut consulter l'arborescence des composants constituant notre application (Screenshot 2).

Nous allons maintenant voir quelques erreurs et bugs qui peuvent survenir et comment les React DevTools peuvent nous aider à les détecter et déboguer.

Erreur liée aux clés dans une liste (Screenshot 3) : Cette erreur apparait quand un élément d'une liste n'a pas une clé unique. Pour la corriger, on ajoute une clé correspondant à l'ID ou le nom de l'élément (une propriété unique (Screenshot 4)

Erreur liée aux props (Screenshot 5) : Quand un composant reçoit des props incorrectes ou nulles, le composant affiche 'undefined'. Pour traiter cette erreur il faut vérifier dans l'arborescence des composants où la transmission s'est interrompue et remettre les props correctement.

Erreur de state et de rendu: Ici notre état ne se met pas à jour comme prévu (Screenshot 6). On vérifie dans l'onglet 'Components', en sélectionnant le composant concerné et on observe ses props et son state et on corrige le 'setState' dans notre code (Screenshot 7).
