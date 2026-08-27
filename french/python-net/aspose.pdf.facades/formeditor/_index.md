---
title: "FormEditor"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe pour éditer les formulaires (ajout/suppression de champs, etc.)"
type: docs
weight: 110
url: /fr/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

Classe pour éditer les formulaires (ajout/suppression de champs, etc.)

Le type FormEditor expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| FormEditor(src_stream, dest_stream) | Initialise une nouvelle instance de la classe FormEditor |
| FormEditor(src_file_name, dest_file_name) | Initialise une nouvelle instance de la classe FormEditor |
| FormEditor() | Constructeur pour FormEditor. |
| FormEditor(document) | Initialise une nouvelle instance de la classe FormEditor |
| FormEditor(document, dest_file_name) | Initialise une nouvelle instance de la classe FormEditor |
| FormEditor(document, dest_stream) | Initialise une nouvelle instance de la classe FormEditor |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| src_file_name | Obtient ou définit le nom du fichier source. |
| dest_file_name | Obtient ou définit le nom du fichier de destination. |
| src_stream | Obtient ou définit le flux source. |
| dest_stream | Obtient ou définit le flux de destination. |
| items | Définit les éléments qui seront ajoutés à la list box ou à la combo box nouvellement créée. |
| export_items | Définit les options de la combo box avec des valeurs d'exportation. |
| facade | Définit les attributs visuels du champ. |
| radio_gap | Le membre qui enregistre l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50. |
| radio_horiz | Le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est vraie. |
| radio_button_item_size | Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté). |
| submit_flag | Définit les indicateurs de soumission du bouton d'envoi |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(src_file) | Lie le document PDF pour l'édition. |
| bind_pdf(src_stream) | Lie le document PDF pour l'édition. |
| bind_pdf(src_doc) | Lie le document PDF pour l'édition. |
| save() | Enregistre les modifications dans le fichier de destination. |
| save(dest_file) | Enregistre les modifications dans le fichier de destination. |
| save(dest_stream) | Enregistre les modifications dans le fichier de destination. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | Ajoute un champ du type spécifié au formulaire. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | Ajoute un champ du type spécifié au formulaire. |
| copy_inner_field(field_name, new_field_name, page_num) | Copie un champ existant à la même position dans le numéro de page spécifié.<br/>            Un nouveau document sera produit, contenant tout ce que le document source possède, sauf le champ nouvellement copié. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | Copie un champ existant à une nouvelle position spécifiée à la fois par le numéro de page et les coordonnées.<br/>            Un nouveau document sera produit, contenant tout ce que le document source possède, sauf le champ nouvellement copié. |
| copy_outer_field(src_file_name, field_name) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page et les coordonnées d'origine.<br/>            Remarque : uniquement pour les champs AcroForm (excluant les boutons radio). |
| copy_outer_field(src_file_name, field_name, page_num) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les coordonnées d'origine.<br/>             Remarque : uniquement pour les champs AcroForm (excluant les boutons radio). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page et les coordonnées spécifiés.<br/>            Remarque : uniquement pour les champs AcroForm (excluant les boutons radio). |
| decorate_field(field_name) | Modifie les attributs visuels du champ spécifié. |
| decorate_field(field_type) | Modifie les attributs visuels de tous les champs du type de champ spécifié. |
| decorate_field() | Modifie les attributs visuels du champ spécifié. |
| add_list_item(field_name, item_name) | Ajoute un nouvel élément à la zone de liste. |
| add_list_item(field_name, export_name) | Ajoute un nouvel élément avec la valeur Export au champ de zone de liste existant, uniquement pour le champ de boîte combinée AcroForm. |
| close() | Ferme la façade. |
| set_field_attribute(field_name, flag) | Définit les attributs du champ. |
| set_field_appearance(field_name, flags) | Définit les indicateurs du champ |
| get_field_appearance(field_name) | Obtient les indicateurs du champ. |
| set_submit_flag(field_name, submit_form_flag) | Définit l'indicateur de soumission du bouton de soumission. |
| set_submit_url(field_name, url) | Définit l'URL du bouton. |
| set_field_limit(field_name, field_limit) | Définit le nombre maximal de caractères du champ texte. |
| set_field_comb_number(field_name, comb_number) | Définit le nombre de créneaux pour un champ texte à ligne unique standard (le champ est <br/>            automatiquement divisé en autant de positions également espacées, ou créneaux, <br/>            que la valeur du paramètre combNumber). |
| move_field(field_name, llx, lly, urx, ury) | Définit la nouvelle position du champ. |
| remove_field(field_name) | Supprime le champ du formulaire. |
| reset_facade() | Réinitialiser tous les attributs visuels à une valeur vide. |
| reset_inner_facade() | Réinitialiser tous les attributs visuels de la façade interne à une valeur vide. |
| rename_field(field_name, new_field_name) | Modifier le nom du champ. |
| remove_field_action(field_name) | Supprimer l'action de soumission du champ. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | Ajouter un bouton de soumission sur le formulaire. |
| del_list_item(field_name, item_name) | Supprimer l'élément du champ de liste. |
| set_field_script(field_name, script) | Définir le JavaScript pour un champ PushButton. Si un ancien JavaScript existait, il sera remplacé par le nouveau. |
| add_field_script(field_name, script) | Ajouter du JavaScript pour un champ PushButton. Si un ancien événement existe, le nouvel événement est ajouté après celui-ci. |
| single_2_multiple(field_name) | Transformer un champ texte à ligne unique en un champ texte à lignes multiples. |
| set_field_alignment(field_name, alignment) | Définir le style d'alignement d'un champ texte. |
| set_field_alignment_v(field_name, alignment) | Définir le style d'alignement vertical d'un champ texte. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

