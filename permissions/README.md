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
- `11-directories_permissions` : ajoute le droit d'exécution à tout le monde sur les sous-dossiers, sans toucher aux fichiers normaux.
- `12-directory_permissions` : crée le dossier my_dir avec les permissions 751.
- `13-change_group` : change le groupe propriétaire du fichier hello en school.
- `14-change_owner_and_group` : change le propriétaire en vincent et le groupe en staff pour tous les fichiers et dossiers du dossier courant.
- `15-symbolic_link_permissions` : change le propriétaire et le groupe du lien symbolique _hello en vincent et staff (le lien lui-même, pas sa cible).
- `16-if_only` : change le propriétaire de hello en vincent seulement s'il appartient à guillaume.
