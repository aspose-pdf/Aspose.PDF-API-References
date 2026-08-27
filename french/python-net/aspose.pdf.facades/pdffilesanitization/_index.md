---
title: "PdfFileSanitization"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente l'API de désinfection et de récupération.<br/>            Utilisez-la si vous ne pouvez pas créer/ouvrir des documents d'une autre manière."
type: docs
weight: 290
url: /fr/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

Représente l'API de désinfection et de récupération.<br/>            Utilisez-la si vous ne pouvez pas créer/ouvrir des documents d'une autre manière.

Le type PdfFileSanitization expose les membres suivants:
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfFileSanitization() | Initialise une nouvelle instance de la classe PdfFileSanitization |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| log | Après que le fichier a été enregistré, vous pouvez vérifier ce qui a été fait avec le fichier. |
| use_trim_top | Permet de supprimer les données avant les données PDF. |
| use_trim_bottom | Permet de supprimer les données après les données PDF |
| use_rebuild_xref_and_trailer | Permet de générer un nouveau xref et trailer pour le document. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(input_file) | Lie un fichier Pdf pour Sanitize. |
| bind_pdf(input_stream) | Lie un flux Pdf pour Sanitize. |
| bind_pdf(src_doc) | Initialise la façade. |
| save(output_file) | Enregistre le PDF résultant dans un fichier. |
| save(output_stream) | Enregistre le PDF résultant dans un flux. |
| close() | Ferme la façade. |
| recover() | Récupère le document.<br/>            Utilisez les propriétés pour personnaliser. |
| trim_top() | Supprime les données avant %PDF. |
| trim_bottom() | Supprime les données après le dernier %%EOF. |
| rebuild_xref_and_trailer() | Supprime l'ancien xref avec trailer et crée un nouveau xref avec trailer. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

