---
title: "ButtonField"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représente le champ de bouton poussoir."
type: docs
weight: 20
url: /fr/python-net/aspose.pdf.forms/buttonfield/
---

## ButtonField class

Classe représente le champ de bouton poussoir.

Le type ButtonField expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| ButtonField() | Constructeur de champ bouton pour Generator. |
| ButtonField(page, rect) | Initialise une nouvelle instance de la classe ButtonField |
| ButtonField(doc, rect) | Initialise une nouvelle instance de la classe ButtonField |
## Propriétés
| Nom | Description |
| :- | :- |
| vertical_alignment | Aucun |
| horizontal_alignment | Aucun |
| marge | Aucun |
| is_first_paragraph_in_column | Aucun |
| is_kept_with_next | Aucun |
| is_in_new_page | Aucun |
| is_in_line_paragraph | Aucun |
| hyperlien | Aucun |
| z_index | Aucun |
| mettre_a_jour_apparence_a_la_conversion | Aucun |
| utiliser_sous_ensemble_de_police | Aucun |
| drapeaux | Aucun |
| type_annotation | Obtient le type de l'annotation. |
| largeur | Aucun |
| actions | Obtient les actions de l'annotation. |
| hauteur | Aucun |
| rect | Obtient ou définit le rectangle du champ. |
| contenu | Aucun |
| nom | Aucun |
| modifié | Aucun |
| couleur | Aucun |
| bordure | Aucun |
| etat_actif | Aucun |
| caractéristiques | Aucun |
| états | Aucun |
| alignement | Aucun |
| alignement_horizontal_texte | Aucun |
| nom_complet | Aucun |
| apparence | Aucun |
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
| normal_caption | Obtient ou définit la légende normale. |
| rollover_caption | Obtient ou définit la légende de survol du bouton qui doit être affichée lorsque l'utilisateur déplace le curseur <br/>            dans sa zone active sans appuyer sur le bouton de la souris. |
| alternate_caption | Obtient ou définit la légende alternative du bouton qui doit être affichée <br/>            lorsque le bouton de la souris est enfoncé dans sa zone active. |
| normal_icon | Obtient ou définit l'icône normale du bouton qui doit être affichée lorsqu'il n'interagit pas avec l'utilisateur. |
| rollover_icon | Obtient ou définit l'icône de survol du bouton qui doit être affichée lorsque l'utilisateur <br/>            déplace le curseur dans sa zone active sans appuyer sur le bouton de la souris. |
| alternate_icon | Obtient ou définit l'icône alternative qui doit être affichée lorsque le bouton de la souris est enfoncé dans sa zone active. |
| icon_fit | Obtient l'objet d'ajustement d'icône spécifiant comment l'icône de l'annotation du widget doit être affichée dans son rectangle d'annotation. |
| ic_position | Obtient ou définit la position de la légende de l'icône. |
## Indexer
| Nom | Description |
| :- | :- |
| [index] | Obtient le sous‑champ contenu dans ce champ par index. |
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Aucun |
| get_rectangle(consider_rotation) | Aucun |
| accept(visitor) | Accepte le visiteur. |
| flatten() | Supprime ce champ et place sa valeur directement sur la page. |
| change_after_resize(transform) | Aucun |
| recalculate() | Recalcule tous les champs calculés du formulaire. |
| copy_to(array, index) | Copie les sous‑champs de ce champ dans le tableau à partir de l’index spécifié. |
| set_position(point) | Définit la position du champ. |
| add_image(image) | Ajoute une image aux ressources du champ et la dessine. |

### Voir aussi

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

