---
title: "PdfExtractor"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe pour extraire des images et du texte d'un document PDF."
type: docs
weight: 210
url: /fr/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

Classe pour extraire des images et du texte d'un document PDF.

Le type PdfExtractor expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfExtractor() | Initialise un nouvel objet [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/). |
| PdfExtractor(document) | Initialise une nouvelle instance de la classe PdfExtractor |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| start_page | Obtient ou définit la page de début dans la plage de pages où l'opération d'extraction sera effectuée. |
| end_page | Obtient ou définit la page de fin dans la plage de pages où l'opération d'extraction sera effectuée. |
| extract_text_mode | Définit le mode du résultat d'extraction de texte. |
| text_search_options | Obtient ou définit les options de recherche de texte. |
| extract_image_mode | Définit le mode du processus d'extraction d'images. |
| is_bidi | Est vrai lorsque le texte contient des symboles hébreux ou arabes. Ce cas doit être spécialement pris en compte car<br/>            les fonctions de chaîne changent leur comportement et commencent le traitement du texte de droite à gauche (excepté les chiffres <br/>            et les autres caractères non textuels). |
| resolution | Définit ou obtient la résolution des images extraites.<br/>            La valeur par défaut est 150.<br/>            Les images ayant une résolution supérieure sont plus nettes.<br/>            Cependant, augmenter la résolution entraîne une augmentation du temps et de la mémoire nécessaires à l'extraction des images.<br/>            En général, pour obtenir une image nette, il suffit de régler la résolution à 150 ou 300. |
| password | Obtient ou définit le mot de passe du fichier d'entrée. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(input_file) | Lie le fichier PDF d'entrée. |
| bind_pdf(input_stream) | Lie le document PDF depuis le flux. |
| bind_pdf(src_doc) | Initialise la façade. |
| extract_text() | Extrait le texte d'un document PDF en utilisant l'encodage Unicode. |
| extract_text(encoding) | Extrait le texte d'un document PDF en utilisant l'encodage spécifié. |
| get_text(output_file) | Enregistre le texte dans un fichier. voir aussi :[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | Enregistre le texte dans le flux. voir aussi :[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | Enregistre le texte dans le flux. voir aussi :[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | Récupère l'image suivante du document PDF. Remarque : ExtractImage doit être appelé avant l'utilisation de cette méthode. |
| get_next_image(output_file, format) | Récupère l'image suivante du document PDF avec le format d'image donné. Remarque : ExtractImage doit être appelé avant l'utilisation de cette méthode. |
| get_next_image(output_stream, format) | Récupère l'image suivante du fichier PDF et la stocke dans le flux avec le format d'image donné. |
| get_next_image(output_stream) | Récupère l'image suivante du fichier PDF et la stocke dans le flux avec le format d'image donné. |
| extract_attachment() | Extrait les pièces jointes d'un document PDF. |
| extract_attachment(attachment_file_name) | Extrait la pièce jointe vers le fichier PDF par le nom de la pièce jointe. |
| get_next_page_text(output_file) | Enregistre le texte d'une page dans un fichier. |
| get_next_page_text(output_stream) | Enregistre le texte d'une page dans un flux. |
| close() | Libère Aspose.Pdf.Document lié à une façade. |
| extract_image() | Extrait les images du fichier PDF. |
| has_next_image() | Vérifie si d'autres images sont accessibles dans le document PDF. Note : ExtractImage doit être appelé avant l'utilisation de cette méthode. |
| get_attach_names() | Renvoie la liste des pièces jointes du fichier PDF. Note : ExtractAttachments doit être appelé avant l'utilisation de cette méthode. |
| get_attachment(output_path) | Enregistre la pièce jointe dans un fichier. |
| has_next_page_text() | Indique s'il est possible d'obtenir plus de textes ou non. |
| get_attachment_info() | Obtient la liste des pièces jointes. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

