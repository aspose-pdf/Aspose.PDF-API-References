---
title: "PdfFileStamp"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe permettant d'ajouter des tampons (filigrane ou arrière-plan) aux fichiers PDF."
type: docs
weight: 320
url: /fr/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

Classe permettant d'ajouter des tampons (filigrane ou arrière-plan) aux fichiers PDF.

Le type PdfFileStamp expose les membres suivants:
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfFileStamp(input_file, output_file) | Initialise une nouvelle instance de la classe PdfFileStamp |
| PdfFileStamp(input_stream, output_stream) | Initialise une nouvelle instance de la classe PdfFileStamp |
| PdfFileStamp(input_file, output_file, keep_security) | Initialise une nouvelle instance de la classe PdfFileStamp |
| PdfFileStamp(input_stream, output_stream, keep_security) | Initialise une nouvelle instance de la classe PdfFileStamp |
| PdfFileStamp() | Constructeur de PdfFileStamp.<br/>            Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. |
| PdfFileStamp(document) | Initialise une nouvelle instance de la classe PdfFileStamp |
| PdfFileStamp(document, output_file) | Initialise une nouvelle instance de la classe PdfFileStamp |
| PdfFileStamp(document, output_stream) | Initialise une nouvelle instance de la classe PdfFileStamp |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| optimize_size | Obtient ou définit le drapeau d'optimisation. Les flux de ressources égaux dans le fichier résultant sont fusionnés en un seul objet PDF si ce drapeau est activé.<br/>            Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des exigences de mémoire plus importantes.<br/>            Valeur par défaut : false. |
| keep_security | Conserve la sécurité si vrai. (Cette fonctionnalité sera implémentée dans les prochaines versions). |
| input_file | Obtient ou définit le nom et le chemin du fichier d'entrée. |
| input_stream | Obtient ou définit le flux d'entrée. |
| output_file | Obtient ou définit le nom et le chemin du fichier de sortie. |
| output_stream | Obtient ou définit le flux de sortie. |
| page_number_rotation | Obtient ou définit la rotation du numéro de page. La rotation est exprimée en degrés. La valeur par défaut est 0. |
| page_height | Obtient la hauteur de la première page dans le fichier source. |
| page_width | Obtient la largeur de la première page dans le fichier d'entrée. |
| starting_number | Obtient ou définit le numéro de départ pour la première page du fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur.<br/>            Par exemple, si StartingNumber est fixé à 100, les pages du document auront les numéros 100, 101, 102... |
| numbering_style | Obtient ou définit le style de numérotation des pages. Valeurs possibles : NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | ID du tampon du prochain tampon ajouté (incluant les en-têtes de page, les pieds de page et les numéros de page). |
| POS_BOTTOM_MIDDLE | Position du milieu inférieur. |
| POS_BOTTOM_RIGHT | Position en bas à droite. |
| POS_UPPER_RIGHT | Position en haut à droite. |
| POS_SIDES_RIGHT | Position à droite. |
| POS_UPPER_MIDDLE | Position du milieu supérieur. |
| POS_BOTTOM_LEFT | Position en bas à gauche. |
| POS_SIDES_LEFT | Position à gauche. |
| POS_UPPER_LEFT | Position supérieure let. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(src_file) | Lie le document PDF pour l'édition. |
| bind_pdf(src_stream) | Lie le document PDF pour l'édition. |
| bind_pdf(src_doc) | Lie le document PDF pour l'édition. |
| save(dest_file) | Enregistre le résultat dans le fichier spécifié. |
| save(dest_stream) | Enregistre le document dans le flux spécifié. |
| add_page_number(format_string) | Ajoute le numéro de page au fichier. Le texte du numéro de page peut contenir le signe # qui sera remplacé par le numéro de la page. <br/>            Le numéro de page est placé en bas de la page, centré horizontalement. |
| add_page_number(formatted_text) | Ajoute le numéro de page à la page. Le numéro de page peut contenir le signe # qui sera remplacé par le numéro de page.<br/>            Le numéro de page est placé en bas de la page, centré horizontalement. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | Ajoute le numéro de page aux pages du document. |
| add_page_number(format_string, x, y) | Ajoute le numéro de page aux pages du document. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | Ajoute le numéro de page aux pages du document. |
| add_page_number(formatted_text, x, y) | Ajoute le numéro de page aux pages du document. |
| add_page_number(format_string, position) | Ajoute le numéro de page aux pages du document. |
| add_page_number(formatted_text, position) | Ajoute le numéro de page aux pages du document. |
| add_header(formatted_text, top_margin) | Ajoute un en-tête à la page. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | Ajoute un en-tête à la page. |
| add_header(image_file, top_margin) | Ajoute une image en tant qu'en-tête aux pages du fichier. |
| add_header(image_file, top_margin, left_margin, right_margin) | Ajoute une image en tant qu'en-tête aux pages du fichier. |
| add_header(image_stream, top_margin) | Ajoute une image en tant qu'en-tête sur les pages. |
| add_header(input_stream, top_margin, left_margin, right_margin) | Ajoute une image en tant qu'en-tête sur les pages. |
| add_footer(formatted_text, bottom_margin) | Ajoute un pied de page aux pages du document. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | Ajoute un pied de page aux pages du document. |
| add_footer(image_file, bottom_margin) | Ajoute une image en tant que pied de page aux pages du document. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | Ajoute une image en tant que pied de page aux pages du document. |
| add_footer(image_stream, bottom_margin) | Ajoute une image en tant que pied de page de la page. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | Ajoute une image en tant que pied de page de la page. |
| close() | Ferme les fichiers ouverts et enregistre les modifications. <br/>            Avertissement. Si des flux d'entrée ou de sortie sont spécifiés, ils ne sont pas fermés par la méthode Close(). |
| add_stamp(stamp) | Ajoute un tampon au fichier. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

