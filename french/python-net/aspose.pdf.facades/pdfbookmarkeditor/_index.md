---
title: "PdfBookmarkEditor"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe pour gérer les signets d'un fichier PDF, y compris la création, la modification, l'exportation, l'importation et la suppression."
type: docs
weight: 180
url: /fr/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

Représente une classe pour gérer les signets d'un fichier PDF, y compris la création, la modification, l'exportation, l'importation et la suppression.

Le type PdfBookmarkEditor expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfBookmarkEditor() | Initialise un nouvel objet [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/) . |
| PdfBookmarkEditor(document) | Initialise une nouvelle instance de la classe PdfBookmarkEditor |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(src_file) | Lie le document PDF pour l'édition. |
| bind_pdf(src_stream) | Lie le document PDF pour l'édition. |
| bind_pdf(src_doc) | Lie le document PDF pour l'édition. |
| save(dest_file) | Enregistre le document PDF dans le fichier spécifié. |
| save(dest_stream) | Enregistre le document PDF dans le flux spécifié. |
| create_bookmarks() | Crée des signets pour toutes les pages. |
| create_bookmarks(bookmark) | Crée des signets pour toutes les pages. |
| create_bookmarks(color, bold_flag, italic_flag) | Créer des signets pour toutes les pages avec la couleur et le style spécifiés (gras, italique). |
| create_bookmark_of_page(bookmark_name, page_number) | Crée un signet pour la page spécifiée. |
| create_bookmark_of_page(bookmark_name, page_number) | Crée des signets pour les pages spécifiées. |
| delete_bookmarks() | Supprime tous les signets du document PDF. |
| delete_bookmarks(title) | Supprime le signet du document PDF. |
| extract_bookmarks() | Extrait les signets de tous les niveaux du document. |
| extract_bookmarks(upper_level) | Extrait les signets de tous les niveaux du document. |
| extract_bookmarks(title) | Extrait les signets avec le titre spécifié. |
| extract_bookmarks(bookmark) | Extrait les signets de tous les niveaux du document. |
| export_bookmarks_to_xml(xml_file) | Exporte les signets vers un fichier XML. |
| export_bookmarks_to_xml(stream) | Exporte les signets vers un flux XML. |
| import_bookmarks_with_xml(xml_file) | Importe les signets dans le document depuis un fichier XML. |
| import_bookmarks_with_xml(stream) | Importe les signets dans le document depuis un fichier XML. |
| close() | Libère toutes les ressources associées à la façade actuelle. |
| modify_bookmarks(s_title, d_title) | Modifie le titre du signet selon le titre de signet spécifié. |
| extract_bookmarks_to_html(pdf_file, css_file) | Exporte les signets vers un fichier HTML. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | Exporte les signets vers un fichier HTML. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

