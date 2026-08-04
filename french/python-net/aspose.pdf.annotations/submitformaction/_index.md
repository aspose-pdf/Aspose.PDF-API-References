---
title: "SubmitFormAction"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe décrivant l'action submit-form."
type: docs
weight: 810
url: /fr/python-net/aspose.pdf.annotations/submitformaction/
---

## SubmitFormAction class

Classe décrivant l'action submit-form.

Le type SubmitFormAction expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| SubmitFormAction() | Initialise l'objet SubmitFormAction. |
## Propriétés
| Nom | Description |
| :- | :- |
| suivant | Actions suivantes dans la séquence. |
| drapeaux | Obtient ou définit les indicateurs de l'action de soumission. |
| url | URL de destination. |
| EXCLUDE | Si vide, le tableau Fields spécifie quels champs inclure dans la soumission. |
| INCLUDE_NO_VALUE_FIELDS | Si défini, tous les champs désignés par le tableau Fields et le drapeau Include/Exclude seront soumis. |
| EXPORT_FORMAT | Si défini, les noms de champs et les valeurs seront soumis au format HTML Form. |
| GET_METHOD | Si défini, les noms de champs et les valeurs seront soumis à l'aide d'une requête HTTP GET. |
| SUBMIT_COORDINATES | Si défini, les coordonnées du clic de souris qui a déclenché l'action submit-form seront transmises dans les données du formulaire. |
| XFDF | Si défini, les noms de champs et les valeurs seront soumis au format XFDF. |
| INCLUDE_APPEND_SAVES | Si défini, le fichier FDF soumis inclura le contenu de toutes les mises à jour incrémentielles. |
| INCLUDE_ANNOTATIONS | Si défini, le fichier FDF soumis inclura toutes les annotations de balisage dans le document PDF sous-jacent. |
| SUBMIT_PDF | Si défini, le document sera soumis au format PDF, en utilisant le type de contenu MIME application/pdf. |
| CANONICAL_FORMAT | Si défini, toutes les valeurs de champ soumises représentant des dates seront converties au format standard. |
| EXCL_NON_USER_ANNOTS | Si défini, il n'inclura que les annotations de balisage dont l'entrée T correspond au nom de l'utilisateur actuel. |
| EXCL_F_KEY | Si défini, le FDF soumis exclura l'entrée F. |
| EMBED_FORM | Si défini, l'entrée F du FDF soumis sera une spécification de fichier contenant un <br/>            flux de fichier intégré représentant le fichier PDF à partir duquel le FDF est soumis. |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

