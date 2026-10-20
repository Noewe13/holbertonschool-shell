# Shell, permissions

- `0-iam_betty` : bascule l'utilisateur courant vers l'utilisateur betty.
- `1-who_am_i` : affiche le nom d'utilisateur effectif de l'utilisateur courant.
- `2-groups` : affiche tous les groupes dont l'utilisateur courant fait partie.
- `3-new_owner` : change le propriétaire du fichier hello en betty.
- `4-empty` : crée un fichier vide appelé hello.
- `5-execute` : ajoute le droit d'exécution au propriétaire du fichier hello.
- `6-multiple_permissions` : ajoute l'exécution au propriétaire et au groupe, et la lecture aux autres, sur le fichier hello.
- `7-everybody` : ajoute le droit d'exécution à tout le monde (propriétaire, groupe, autres) sur le fichier hello.
- `8-James_Bond` : fixe les permissions de hello à 007 (rien pour le propriétaire et le groupe, tout pour les autres).
- `9-John_Doe` : fixe les permissions de hello à 753 (-rwxr-x-wx).
- `10-mirror_permissions` : donne à hello les mêmes permissions que olleh.
