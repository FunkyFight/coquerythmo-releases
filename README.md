# coquerythmo-releases
Bande rythmo simple, épurée et optimisée. Tout ça, gratuitement.

## Version 3.5.4

Cette version améliore fortement l’accessibilité clavier et la lecture vocale.
Sous Windows, les annonces sont transmises au système d’accessibilité via
AccessKit. Les raccourcis utilisés sont annoncés automatiquement, les listes
annoncent leur premier élément puis leur état « réduite » à la fermeture, et
les modales annoncent leur fermeture.

Avec la lecture vocale active sous Windows, les sélecteurs de fichiers utilisent
l’Explorateur Windows natif. Les projets `.coquerythmo` peuvent également être
ouverts avec Coquerythmo depuis le menu « Ouvrir avec » de Windows.

La liste complète des raccourcis est disponible dans
[`RACCOURCIS_CLAVIER.md`](RACCOURCIS_CLAVIER.md).

## Tutoriels
[![Tutoriel français](https://img.youtube.com/vi/m_SpxXRjvmg/maxresdefault.jpg)](https://www.youtube.com/watch?v=m_SpxXRjvmg)
[Tutoriel français](https://www.youtube.com/watch?v=m_SpxXRjvmg)

[![V3.4.0 (Pro Tools)](https://img.youtube.com/vi/nKFU_zl7Duc/maxresdefault.jpg)](https://www.youtube.com/watch?v=nKFU_zl7Duc)
[V3.4.0](https://www.youtube.com/watch?v=nKFU_zl7Duc)

[![Tutoriel français BANDE RYTHMO ENSEMBLE](https://img.youtube.com/vi/rJi6mt2Jax4/maxresdefault.jpg)](https://www.youtube.com/watch?v=rJi6mt2Jax4)
[Tutoriel français BANDE RYTHMO ENSEMBLE](https://www.youtube.com/watch?v=rJi6mt2Jax4)

## Raccourcis clavier

Les raccourcis sont interprétés selon le contexte actif. Un champ texte est
prioritaire sur les raccourcis de l’espace de travail. Dans une modale, le
focus reste enfermé dans la modale jusqu’à sa fermeture.

Chaque raccourci clavier utilisé est annoncé automatiquement, y compris dans
les champs texte et les modales.

### Navigation commune

| Raccourci | Action | Contexte |
|---|---|---|
| `Tab` | Focus suivant | Contrôles, listes, menus et modales |
| `Maj + Tab` | Focus précédent | Contrôles, listes, menus et modales |
| `Entrée` / `Espace` | Activer le contrôle focalisé | Contrôles, listes, menus et modales |
| `Échap` | Fermer le niveau courant ou annuler | Modales, menus et éditeurs |
| `↑` / `↓` | Parcourir une liste ou modifier une valeur | Contrôles focalisés |
| `←` / `→` | Parcourir ou régler le contrôle | Contrôles focalisés |
| `Début` / `Fin` | Aller au premier/dernier élément | Listes et contrôles |
| `Page haut` / `Page bas` | Parcourir par page | Listes |
| `Maj + F10` | Ouvrir le menu contextuel de l’élément focalisé | Contrôles et lignes |

### Barre supérieure et projet

| Raccourci | Action |
|---|---|
| `Ctrl + S` | Sauvegarde rapide |
| `Ctrl + Maj + I` | Importer un sous-titrage (`.coquerythmo`, `.json`, `.srt`, `.ass`, `.detx`) |
| `Ctrl + Maj + R` | Restaurer la dernière sauvegarde disponible |
| `Ctrl + R` | Ouvrir les projets récents |
| `Ctrl + Suppr` | Fermer le projet |
| `Ctrl + M` | Ouvrir l’export du projet |
| `Ctrl + Alt + S` | Afficher l’avertissement et ouvrir le mode Studio |
| `Ctrl + Maj + P` | Renommer le personnage sélectionné |
| `Ctrl + O` | Ouvrir les paramètres du projet |
| `Ctrl + N` | Créer un nouveau projet |
| `Ctrl + I` | Ouvrir le panneau des lignes |
| `Ctrl + P` | Ouvrir le panneau des rôles |
| `Ctrl + L` | Ouvrir le sélecteur de langues (hors modale) |
| `F5` | Afficher l’avertissement Studio lorsqu’une vidéo est chargée |

Dans la liste des projets récents : `↑`/`↓` parcourent les projets, `Entrée`
ouvre le projet, `Suppr` le retire de la liste et `Échap` ferme la liste.

### Outils et lecture

| Raccourci | Action |
|---|---|
| `Ctrl + ←` / `Ctrl + →` | Image précédente/suivante |
| `Numpad 1` | Ajouter une boucle |
| `Numpad 2` | Ajouter un point Out |
| `Numpad 3` | Ajouter un changement de scène |
| `Numpad 4` | Ouvrir les respirations |
| `Numpad 5` | Ouvrir les réactions |
| `Numpad 6` | Ajouter une note |
| `Numpad 7` / `Numpad 8` | Ajouter une liaison à gauche/droite |
| `Numpad 9` | Activer/désactiver le karaoké |
| `Ctrl + Numpad 1` à `Ctrl + Numpad 4` | Créer une ligne sur la piste 1 à 4 |
| `C` | Outil Sélection |
| `Ctrl + D` | Outil Dessin |
| `Maj + ↑` / `Maj + ↓` | Augmenter/diminuer le volume par pas de 5 % |
| `Maj + Numpad -` | Activer/désactiver le muet |
| `Espace` | Lecture/pause |
| `Ctrl + Tab` | Basculer entre l’audio original et l’audio instrumental |

### Bande rythmo

| Raccourci | Action |
|---|---|
| `Entrée` | Sélectionner successivement les lignes présentes au frame courant |
| `↑` / `↓` (ligne sélectionnée) | Déplacer la ligne vers la piste précédente/suivante |
| `Maj + ←` / `Maj + →` (ligne sélectionnée) | Décaler la ligne d’une frame |
| `I` / `O` | Fixer le début/la fin de la ligne sélectionnée |
| `Q` / `D` (maintenir) | Déplacer continuellement la timeline à gauche/droite |
| `T` | Modifier le texte de la ligne sélectionnée |
| `P` | Modifier le personnage de la ligne sélectionnée |
| `Suppr` | Supprimer la ligne sélectionnée |
| `Ctrl + C` | Copier la ligne sélectionnée |
| `Ctrl + X` | Couper la ligne sélectionnée |
| `Ctrl + V` | Coller la ligne sur la piste sous le curseur de souris |

Si la souris est hors de la bande rythmo, `Ctrl + V` utilise la piste clavier
active. Pendant l’édition d’une ligne ou d’un personnage, les flèches déplacent
le caret et ne modifient pas le volume.

### Export

| Raccourci | Action |
|---|---|
| `Tab` / `Maj + Tab` | Parcourir tous les réglages, formats, langues et boutons |
| `↑` / `↓` sur le menu des pages | Passer entre Vidéo, Sous-titres, Audio et Références |
| `←` / `→` sur le menu des pages | Passer entre les pages d’export |
| `↑` / `↓` sur un réglage | Modifier sa valeur |
| `Entrée` / `Espace` | Activer un format, une langue ou un bouton |
| `Échap` | Fermer l’export |

Les champs largeur et hauteur acceptent les chiffres, `Retour arrière` et
`Entrée` termine leur édition.

### Champs texte et modales

| Raccourci | Action |
|---|---|
| `Ctrl + A` | Tout sélectionner |
| `Ctrl + C` / `Ctrl + X` / `Ctrl + V` | Copier/couper/coller le texte |
| `Ctrl + Z` | Annuler |
| `Ctrl + Maj + Z` | Rétablir |
| `←` / `→` | Déplacer le caret |
| `Maj + ←` / `Maj + →` | Étendre la sélection |
| `↑` / `↓` | Parcourir les suggestions ou les éléments de liste |
| `Retour arrière` / `Suppr` | Supprimer le caractère précédent/suivant |

Dans l’Explorateur de fichiers, `Alt + ←`/`Alt + →` parcourent l’historique,
`Retour arrière` remonte au dossier parent et `Entrée` ouvre le fichier ou
valide l’action principale.

### Lecture vocale interne

| Raccourci | Action |
|---|---|
| `Ctrl + Maj + N` | Activer/désactiver la lecture vocale interne |
| `Ctrl` | Interrompre la lecture vocale en cours |
| `Maj` | Reprendre la lecture vocale interrompue |

Chaque changement de focus, sélection, activation, valeur et résultat d’action
est annoncé. Pour `Q`/`D`, le timecode est annoncé une seule fois au
relâchement de la touche, avec les heures, minutes, secondes et centièmes.

L’ouverture d’une liste annonce son premier élément disponible. Sa fermeture
annonce que la liste est réduite. La fermeture d’une modale est également
annoncée.

Sur Linux, la lecture vocale interne reste indisponible et le raccourci affiche
un message localisé.
