---
title: "PdfContentEditor"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe pour modifier le contenu d'un fichier PDF."
type: docs
weight: 190
url: /fr/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

Représente une classe pour modifier le contenu d'un fichier PDF.

Le type PdfContentEditor expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfContentEditor() | Le constructeur de l'objet PdfContentEditor. |
| PdfContentEditor(document) | Initialise une nouvelle instance de la classe PdfContentEditor |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| text_search_options | Obtient ou définit les options de recherche de texte. |
| text_edit_options | Obtient ou définit les options de modification de texte. |
| text_replace_options | Obtient ou définit les options de remplacement de texte. |
| replace_text_strategy | Un ensemble de paramètres pour l'opération de remplacement de texte |
| DOCUMENT_OPEN | Un type d'événement de document. Ouvre un document. |
| DOCUMENT_CLOSE | Un type d'événement de document. Ferme un document. |
| DOCUMENT_WILL_SAVE | Un type d'événement de document. Exécute une action avant l'enregistrement. |
| DOCUMENT_SAVED | Un type d'événement de document. Exécute une action après l'enregistrement. |
| DOCUMENT_WILL_PRINT | Un type d'événement de document. Exécute une action avant l'impression. |
| DOCUMENT_PRINTED | Un type d'événement de document. Exécute une action après l'impression. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(input_file) | Lie un fichier PDF pour la modification. |
| bind_pdf(input_stream) | Lie un flux PDF pour la modification. |
| bind_pdf(src_doc) | Lie le document PDF pour l'édition. |
| save(dest_file) | Enregistre le document PDF dans le fichier spécifié. |
| save(dest_stream) | Enregistre le document PDF dans le flux spécifié. |
| create_web_link(rect, url, original_page, clr) | Crée un lien web dans le document PDF. |
| create_web_link(rect, url, original_page) | Crée un lien web dans le document PDF. |
| create_local_link(rect, des_page, original_page, clr) | Crée un lien local dans le document PDF. |
| create_local_link(rect, des_page, original_page) | Crée un lien local dans le document PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | Crée un lien vers une autre page de document PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | Crée un lien vers une autre page de document PDF. |
| create_application_link(rect, application, page, clr) | Crée un lien pour lancer une application dans le document PDF. |
| create_application_link(rect, application, page) | Crée un lien pour lancer une application dans le document PDF. |
| create_file_attachment(rect, contents, file_path, page, name) | Crée une annotation de pièce jointe de fichier. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | Crée une annotation de pièce jointe de fichier. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | Crée une annotation de pièce jointe de fichier. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | Crée une annotation de pièce jointe de fichier. |
| add_document_attachment(file_attachment_path, description) | Ajoute une pièce jointe de document sans annotation. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | Ajoute une pièce jointe de document sans annotation. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | Crée une annotation de tampon en caoutchouc. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | Crée une annotation de tampon en caoutchouc. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | Crée une annotation de tampon en caoutchouc. |
| delete_image(page_number, index) | Supprime les images spécifiées sur la page indiquée. |
| delete_image() | Supprime les images spécifiées sur la page indiquée. |
| replace_text(src_string, the_page, dest_string, text_state) | Remplace le texte dans le fichier PDF sur la page spécifiée. L'objet [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (famille de police, couleur) peut être spécifié pour le texte remplacé. |
| replace_text(src_string, dest_string) | Remplace le texte dans le fichier PDF sur la page spécifiée. L'objet [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (famille de police, couleur) peut être spécifié pour le texte remplacé. |
| replace_text(src_string, the_page, dest_string) | Remplace le texte dans le fichier PDF sur la page spécifiée. L'objet [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (famille de police, couleur) peut être spécifié pour le texte remplacé. |
| replace_text(src_string, dest_string, text_state) | Remplace le texte dans le fichier PDF sur la page spécifiée. L'objet [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (famille de police, couleur) peut être spécifié pour le texte remplacé. |
| replace_text(src_string, dest_string, font_size) | Remplace le texte dans le fichier PDF sur la page spécifiée. L'objet [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (famille de police, couleur) peut être spécifié pour le texte remplacé. |
| delete_stamp_by_ids(stamp_ids) | Supprime les tampons avec les ID spécifiés de toutes les pages du document. |
| delete_stamp_by_ids(page_number, stamp_ids) | Supprime les tampons avec les ID spécifiés de toutes les pages du document. |
| delete_stamp_by_id(page_number, stamp_id) | Supprime les tampons avec les ID spécifiés de toutes les pages du document. |
| delete_stamp_by_id(stamp_id) | Supprime les tampons avec les ID spécifiés de toutes les pages du document. |
| close() | Ferme le document ouvert. |
| extract_link() | Extrait la collection d'instances de Link contenues dans le document PDF. |
| create_java_script_link(code, rect, original_page, color) | Crée un lien vers JavaScript dans le document PDF. |
| create_text(rect, title, contents, open, icon, page) | Crée une annotation de texte dans le document PDF |
| create_free_text(rect, contents, page) | Crée une annotation de texte libre dans le document PDF |
| create_markup(rect, contents, type, page, clr) | Crée une annotation de balisage dans le document PDF. |
| create_popup(rect, contents, open, page) | Crée une annotation popup dans le document PDF. |
| delete_attachments() | Supprime toutes les pièces jointes du document PDF. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | Crée une annotation de ligne. |
| create_square_circle(rect, contents, clr, square, page, border_width) | Crée une annotation carré-cercle. |
| draw_curve(line_info, page, annot_rect, annot_contents) | Crée une annotation de courbe. |
| create_polygon(line_info, page, annot_rect, annot_contents) | Crée une annotation de polygone. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | Crée une annotation de polyligne. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | Crée une annotation de caret. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | Crée un signet avec l'action spécifiée. |
| add_document_additional_action(event_type, code) | Ajoute une action supplémentaire pour l'événement du document. |
| remove_document_open_action() | Supprime l'action d'ouverture du document. Cette opération est utile lors de la concaténation de plusieurs documents qui utilisent une action 'GoTo' explicite au démarrage. |
| change_viewer_preference(viewer_attribution) | Modifie la préférence d'affichage. |
| get_viewer_preference() | Renvoie la préférence d'affichage. |
| replace_image(page_number, index, image_file) | Remplace l'image spécifiée sur la page spécifiée du document PDF par une autre image. |
| create_movie(rect, file_path, page) | Crée des annotations de film. |
| create_sound(rect, file_path, name, page, rate) | Crée des annotations sonores. |
| delete_stamp(page_number, index) | Supprime plusieurs tampons sur la page spécifiée par les index de tampon. |
| hide_stamp_by_id(page_number, stamp_id) | Masque le tampon. Après masquage, la visibilité du tampon peut être restaurée avec la méthode ShowStampById. |
| show_stamp_by_id(page_number, stamp_id) | Affiche le tampon qui a été masqué par HiddenStampById. |
| move_stamp_by_id(page_number, stamp_id, x, y) | Modifie la position du tampon sur la page. |
| move_stamp(page_number, stamp_index, x, y) | Modifie la position du tampon sur la page. |
| get_stamps(page_number) | Renvoie un tableau de tampons sur la page. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

