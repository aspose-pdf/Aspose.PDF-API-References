---
title: "PdfAnnotationEditor"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe pour travailler avec les annotations (commentaires) d'un document PDF."
type: docs
weight: 170
url: /fr/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

Représente une classe pour travailler avec les annotations (commentaires) d'un document PDF.

Le type PdfAnnotationEditor expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfAnnotationEditor() | Initialise un nouvel objet [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/). |
| PdfAnnotationEditor(document) | Initialise une nouvelle instance de la classe PdfAnnotationEditor |
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
| import_annotations_from_xfdf(xfdf_file) | Importe toutes les annotations du fichier XFDF. |
| import_annotations_from_xfdf(xfdf_stream) | Importe toutes les annotations du flux de données XFDF. |
| import_annotation_from_xfdf(xfdf_file) | Importe toutes les annotations du fichier XFDF. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | Importe les annotations spécifiées du fichier XFDF. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | Importe les annotations spécifiées du flux de données XFDF. |
| import_annotation_from_xfdf(xfdf_stream) | Importe les annotations spécifiées du flux de données XFDF. |
| import_annotations(annot_file, annot_type) | Importe les annotations spécifiées dans le document à partir d'un tableau d'autres documents PDF. |
| import_annotations(annot_file) | Importe les annotations spécifiées dans le document à partir d'un tableau d'autres documents PDF. |
| import_annotations(annot_file_stream, annot_type) | Importe les annotations spécifiées dans le document à partir d'un tableau d'autres flux de documents PDF. |
| import_annotations(annot_file_stream) | Importe les annotations spécifiées dans le document à partir d'un tableau d'autres flux de documents PDF. |
| flattening_annotations() | Aplatisse toutes les annotations du document. |
| flattening_annotations(flatten_settings) | Aplatisse toutes les annotations du document. |
| flattening_annotations(start, end, annot_type) | Aplatisse les annotations des types spécifiés. |
| delete_annotations() | Supprime toutes les annotations du document. |
| delete_annotations(annot_type) | Supprime toutes les annotations du type spécifié dans le document. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Exporte le contenu des types d'annotation spécifiés vers XFDF |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Exporte le contenu des types d'annotation spécifiés vers XFDF |
| extract_annotations(start, end, annot_types) | Obtient la liste des annotations des types spécifiés. |
| extract_annotations(start, end, annot_types) | Obtient la liste des annotations des types spécifiés. |
| close() | Libère toutes les ressources associées à la façade actuelle. |
| modify_annotations_author(start, end, src_author, des_author) | Modifie l'auteur des annotations sur la plage de pages spécifiée. |
| delete_annotation(annot_name) | Supprime toutes les annotations du type spécifié dans le document. |
| export_annotations_to_xfdf(xml_output_stream) | Exporte les annotations vers le flux. |
| modify_annotations(start, end, annotation) | Modifie les annotations du type spécifié sur la plage de pages spécifiée.<br/>            Il prend en charge la modification des propriétés d'annotation suivantes : Modified, Title, Contents, Color, Subject et Open. |
| redact_area(page_index, rect, color) | Masque la zone sur la page spécifiée. Tout le contenu est supprimé. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

