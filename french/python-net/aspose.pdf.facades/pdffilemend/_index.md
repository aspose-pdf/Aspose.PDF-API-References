---
title: "PdfFileMend"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe pour ajouter du texte et des images sur les pages d'un document PDF existant."
type: docs
weight: 280
url: /fr/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

Représente une classe pour ajouter du texte et des images sur les pages d'un document PDF existant.

Le type PdfFileMend expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfFileMend() | Constructeur. |
| PdfFileMend(input_file_name, output_file_name) | Initialise une nouvelle instance de la classe PdfFileMend |
| PdfFileMend(input_stream, output_stream) | Initialise une nouvelle instance de la classe PdfFileMend |
| PdfFileMend(document) | Initialise une nouvelle instance de la classe PdfFileMend |
| PdfFileMend(document, output_file_name) | Initialise une nouvelle instance de la classe PdfFileMend |
| PdfFileMend(document, dest_stream) | Initialise une nouvelle instance de la classe PdfFileMend |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| input_stream | Définit le flux d'entrée. |
| output_stream | Définit le flux de sortie. |
| input_file | Définit le fichier d'entrée. |
| output_file | Définit le fichier de sortie. |
| wrap_mode | Définit ou obtient l'algorithme de retour à la ligne. Voir WordWrapMode et IsWordWrap. |
| text_positioning_mode | Définit ou obtient la stratégie de positionnement du texte. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            Le mode par défaut est Legacy. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(src_file) | Lie le document PDF pour l'édition. |
| bind_pdf(src_stream) | Lie le document PDF pour l'édition. |
| bind_pdf(src_doc) | Lie le document PDF pour l'édition. |
| save(dest_file) | Enregistre le document PDF dans le fichier spécifié. |
| save(dest_stream) | Enregistre le document PDF dans le flux spécifié. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. |
| add_text(text, page_num, lower_left_x, lower_left_y) | Non implémenté. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Non implémenté. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Non implémenté. |
| close() | Ferme l'objet PdfFileMend. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

