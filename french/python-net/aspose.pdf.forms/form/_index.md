---
title: "Form"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représentant l'objet formulaire."
type: docs
weight: 110
url: /fr/python-net/aspose.pdf.forms/form/
---

## Form class

Classe représentant l'objet formulaire.

Le type Form expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| is_synchronized | Renvoie true si l'objet est thread-safe. |
| sync_root | Renvoie l'objet de synchronisation. |
| auto_recalculate | Si défini, tous les champs du formulaire seront recalculés lorsqu'un champ est modifié. La valeur par défaut est true. Définissez à false afin d'améliorer les performances lors du remplissage du formulaire contenant un grand nombre de champs calculés. |
| auto_restore_form | Si défini, les champs de formulaire absents seront créés automatiquement s'ils sont présents dans les annotations. |
| default_resources | Obtient les ressources par défaut placées sur ce formulaire. |
| default_appearance | Obtient ou définit l'apparence par défaut du formulaire (objet qui décrit la police, la taille du texte et la couleur par défaut pour les champs du formulaire). |
| xfa | Obtient les données XFA du formulaire (si présentes). |
| ignore_needs_rendering | Si cette propriété est vraie, la valeur de la clé NeedsRendering sera ignorée lors de la conversion <br/>            du formulaire XFA en formulaire Standard. Elle est fausse par défaut. |
| remove_permission | Si cette propriété est vraie, le dictionnaire "Perms" sera supprimé du document pdf après la conversion <br/>            des documents dynamiques en standard. Le dictionnaire "Perms" peut contenir des règles qui perturbent l'affichage de la sélection de <br/>            champs obligatoires dans le lecteur Adobe Acrobat.<br/>            Il est faux par défaut. |
| emulate_requierd_groups | Si cette propriété est vraie, des rectangles rouges supplémentaires seront dessinés autour des conteneurs d'éléments Xfa exclGroup requis<br/>            Cette propriété a été introduite en raison de l'absence d'analogues pour exclGroup lors de la conversion de la représentation Xfa des formulaires <br/>            en standard.<br/>            Elle est fausse par défaut. |
| type | Obtient le type du formulaire. Les valeurs possibles sont : Standard, Static, Dynamic. |
| fields | Obtient la liste de tous les champs au niveau le plus bas du formulaire hiérarchique. |
| signatures_exist | Si défini, le document contient au moins un champ de signature. |
| signatures_append_only | Si défini, le document contient des signatures qui peuvent être invalidées si le fichier est enregistré (écrit) d'une manière qui modifie son contenu précédent, <br/>            contrairement à une mise à jour incrémentielle. |
| sign_dependent_elements_rendering_mode_when_converted | Les formulaires peuvent contenir des informations de signature, c’est‑à‑dire être signés ou non signés.<br/>              Et la vue du formulaire doit parfois dépendre du fait que le formulaire soit signé ou non.<br/>              Cette propriété indique au convertisseur de formulaire (par ex. lors de la conversion d’un formulaire XFA en formulaire Standard)<br/>              si le formulaire résultant doit être rendu comme signé ou comme non signé. |
## Indexer
| Nom | Description |
| :- | :- |
| [index] | Obtient le champ du formulaire par indice de champ. |
## Méthodes
| Nom | Description |
| :- | :- |
| delete(field) | Supprime le champ du formulaire. |
| delete(field_name) | Supprime le champ du formulaire par son nom. |
| add(field, page_number) | Ajoute un champ au formulaire. |
| add(field) | Ajoute un champ au formulaire. |
| add(field, partial_name, page_number) | Ajoute un nouveau champ au formulaire ; si ce champ est déjà placé sur un autre ou sur ce formulaire, une copie du champ est créée. |
| has_field(field) | Vérifie si le formulaire possède déjà le champ spécifié. |
| has_field(field_name) | Détermine si le champ portant le nom spécifié a déjà été ajouté au formulaire. |
| copy_to(array, index) | Copie les champs placés sur le formulaire dans un tableau. |
| flatten() | Supprime tous les champs du formulaire et place leurs valeurs directement sur la page. |
| add_field_appearance(field, page_number, rect) | Ajoute une apparence supplémentaire du champ à la page spécifiée du document à l'emplacement indiqué. |
| get_fields_in_rect(rect) | Renvoie les champs à l'intérieur du rectangle spécifié. |

### Voir aussi

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

