---
title: "Field"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe de base pour les champs de formulaire Acro."
type: docs
weight: 90
url: /fr/python-net/aspose.pdf.forms/field/
---

## Field class

Classe de base pour les champs de formulaire Acro.

Le type Field expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| Field(doc) | Initialise une nouvelle instance de la classe Field |
## Propriétés
| Nom | Description |
| :- | :- |
| vertical_alignment | Aucun |
| horizontal_alignment | Obtient ou définit l'alignement du texte pour l'annotation. |
| marge | Aucun |
| is_first_paragraph_in_column | Aucun |
| is_kept_with_next | Aucun |
| is_in_new_page | Aucun |
| is_in_line_paragraph | Aucun |
| hyperlien | Aucun |
| z_index | Aucun |
| mettre_a_jour_apparence_a_la_conversion | Si vrai, l'apparence de l'annotation sera mise à jour avant de convertir le document PF en image. Cela permet de convertir correctement les champs mais demande probablement plus de temps. |
| utiliser_sous_ensemble_de_police | Si cette propriété est définie sur true, les polices seront ajoutées au document sous forme de sous-ensembles. La valeur par défaut est true. |
| drapeaux | Drapeaux de l'annotation. |
| type_annotation | Obtient le type de l'annotation. |
| largeur | Obtient ou définit la largeur de l'annotation. |
| actions | Obtient les actions de l'annotation. |
| hauteur | Obtient ou définit la hauteur de l'annotation. |
| rect | Obtient ou définit le rectangle du champ. |
| contenu | Obtient ou définit le texte de l'annotation. |
| nom | Obtient ou définit le nom de l'annotation sur la page. |
| modifié | Obtient ou définit la date et l'heure de la dernière modification de l'annotation. |
| couleur | Obtient ou définit la couleur de l'annotation. |
| border | Obtient ou définit les caractéristiques de la bordure de l'annotation. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| etat_actif | Obtient ou définit l'état d'apparence de l'annotation actuelle. |
| caractéristiques | Obtient les caractéristiques de l'annotation. |
| états | Obtient le dictionnaire d'apparence de l'annotation. |
| alignement | Alignement de l'annotation. Cette propriété est obsolète. Utilisez HorizontalAligment à la place. |
| alignement_horizontal_texte | Obtient ou définit l'alignement du texte pour l'annotation. |
| nom_complet | Obtient le nom complet de l'annotation. |
| apparence | Obtient le dictionnaire d'apparence de l'annotation. |
| indice_page | Obtient l'indice de la page qui contient ce champ. |
| lors_de_l_activation | Une action qui doit être exécutée lorsque l'annotation est activée. |
| mise en évidence | Mode de mise en évidence de l'annotation. |
| parent | Obtient le parent de l'annotation. |
| default_appearance | Obtient ou définit l'apparence par défaut du champ. |
| read_only | Obtient ou définit le statut lecture seule du champ. |
| required | Obtient ou définit le statut requis du champ. |
| exportable | Obtient ou définit le drapeau exportable du champ. |
| partial_name | Obtient ou définit le nom partiel du champ. |
| alternate_name | Obtient ou définit le nom alternatif du champ (Un champ alternatif <br/>            nom qui doit être utilisé à la place du nom réel du champ <br/>            partout où le champ doit être identifié dans l'interface utilisateur).<br/>            Le nom alternatif est utilisé comme info-bulle du champ dans Adobe Acrobat. |
| mapping_name | Obtient ou définit le nom de mappage du champ qui doit être utilisé lors de l'exportation des données de champs de formulaire interactif depuis le document. |
| valeur | Obtient ou définit la valeur du champ. |
| is_synchronized | Renvoie vrai si le dictionnaire est synchronisé. |
| sync_root | Objet de synchronisation. |
| is_group | Obtient ou définit la valeur booléenne qui indique si ce champ est un champ non terminal, c’est‑à‑dire un groupe de champs. |
| annotation_index | Obtient ou définit l'index de cette annotation sur la page. |
| is_shared_field | Propriété pour la prise en charge du générateur. Utilisée lorsque le champ est ajouté à l'en-tête ou au pied de page. Si vrai, ce champ sera créé une fois et son apparence sera visible sur toutes les pages du document. Si faux, un champ séparé sera créé pour chaque page du document. |
| fit_into_rectangle | Si vrai, la taille de la police sera réduite pour ajuster le texte au rectangle spécifié. |
| max_font_size | Taille de police maximale pouvant être utilisée pour le contenu du champ. -1 pour ne pas vérifier la taille. |
| min_font_size | Taille de police minimale pouvant être utilisée pour le contenu du champ. -1 pour ne pas vérifier la taille. |
| tab_order | Obtient ou définit l'ordre de tabulation du champ. |
## Indexer
| Nom | Description |
| :- | :- |
| [index] | Obtient le sous‑champ contenu dans ce champ par index. |
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Aucun |
| get_rectangle(consider_rotation) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |
| accept(visitor) | Accepte le visiteur. |
| flatten() | Supprime ce champ et place sa valeur directement sur la page. |
| change_after_resize(transform) | Met à jour les paramètres et l'apparence, selon la transformation matricielle. |
| recalculate() | Recalcule tous les champs calculés du formulaire. |
| copy_to(array, index) | Copie les sous‑champs de ce champ dans le tableau à partir de l’index spécifié. |
| set_position(point) | Définit la position du champ. |

### Voir aussi

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

