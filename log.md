# Différence entre `git status` et `git log --oneline`

## `git status`
Cette commande permet de voir l'**état actuel** du dépôt de travail (working directory) et de l'espace de préparation (staging area). Elle nous dit :
- Sur quelle branche nous sommes.
- Quels fichiers ont été modifiés, ajoutés ou supprimés.
- Quels fichiers sont prêts à être "commit" (fichiers stagés).

En résumé, c'est idéal pour savoir **"Où en suis-je maintenant et qu'est-ce qui a changé depuis le dernier commit ?"**

## `git log --oneline`
Cette commande affiche l'**historique** des commits qui ont été enregistrés de manière très condensée (une ligne par commit avec le hash raccourci et le message du commit).
Elle nous dit :
- Qui a fait quoi (ou plutôt quels changements ont été entérinés).
- L'ordre chronologique des sauvegardes.

En résumé, c'est idéal pour savoir **"Qu'est-ce qui a déjà été fait et sauvegardé dans le passé ?"**
