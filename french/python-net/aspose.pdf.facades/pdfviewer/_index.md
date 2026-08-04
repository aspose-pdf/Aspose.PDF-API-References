---
title: "PdfViewer"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe permettant de visualiser ou d'imprimer un pdf."
type: docs
weight: 370
url: /fr/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

Représente une classe permettant de visualiser ou d'imprimer un pdf.

Le type PdfViewer expose les membres suivants:
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfViewer() | Initialise un nouveau [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/) objet. |
| PdfViewer(document) | Initialise une nouvelle instance de la classe PdfViewer |
## Propriétés
| Nom | Description |
| :- | :- |
| show_hidden_areas | Obtient ou définit le drapeau qui contrôle la visibilité des zones cachées sur la page. |
| print_status | Obtient le résultat de la tâche d'impression. En cas de succès, null ; sinon, objet d'exception. |
| use_intermidiate_image | Obtient/définit l'utilisation de la conversion de la page pdf en fichier png intermédiaire lors de l'impression en mode fichier. Utilisez-le lorsque la taille du fichier de sortie est importante. |
| coordinate_type | Obtient ou définit le type de coordonnées de la page (Media/Crop boxes). La valeur CropBox est utilisée par défaut. |
| print_as_image | Définit ou obtient un mode pour PdfViewer d'imprimer en tant qu'image. |
| page_count | Obtient le nombre de pages du fichier Pdf actuel. |
| password | Obtient ou définit le mot de passe du document d'entrée. |
| print_page_dialog | Obtient ou définit une valeur booléenne qui indique s'il faut produire la boîte de dialogue du numéro de page lors de l'impression. |
| print_as_grayscale | Obtient ou définit une valeur booléenne qui indique si la page est imprimée en niveaux de gris. Par défaut, c'est false. |
| printer_job_name | Obtient ou définit le nom du document dans la file d'attente de l'imprimante lors de l'impression du document. La valeur par défaut est le nom du fichier. |
| form_presentation_mode | Obtient ou définit le mode de présentation du formulaire. |
| rendering_options | Obtient ou définit les options de rendu. |
| vertical_alignment | Obtient ou définit une valeur qui indique l'alignement vertical |
| horizontal_alignment | Obtient ou définit une valeur qui indique l'alignement horizontal |
| auto_resize | Obtient ou définit une valeur booléenne qui indique si le fichier doit être imprimé avec une taille optimisée. |
| auto_rotate | Obtient ou définit une valeur booléenne qui indique si le fichier doit être imprimé avec rotation automatique |
| auto_rotate_mode | Obtient ou définit une valeur AutoRotateMode qui indique la direction de rotation |
| resolution | Obtient ou définit la résolution lors de la visualisation et de l'impression. Plus la résolution est élevée, plus la vitesse est lente. La valeur par défaut est 150. |
| scale_factor | Obtient ou définit une valeur à virgule flottante qui indique le facteur d'échelle. La valeur par défaut est 1.0. |
## Méthodes
| Nom | Description |
| :- | :- |
| print_large_pdf(file_path) | Ouvre et imprime un gros fichier Pdf. Si votre fichier Pdf comporte des centaines de pages ou plus ou si sa taille est <br/>             supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. |
| print_large_pdf(input_stream) | Ouvre et imprime un gros flux Pdf. Si votre fichier Pdf comporte des centaines de pages ou plus ou si sa taille est <br/>             supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. |
| print_large_pdf(file_path, printer_settings) | Ouvre et imprime un gros fichier Pdf avec les paramètres d'imprimante spécifiés. Si votre fichier Pdf comporte des centaines <br/>             de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. |
| print_large_pdf(input_stream, printer_settings) | Ouvre et imprime un gros flux Pdf avec les paramètres d'imprimante spécifiés. Si votre fichier Pdf comporte des centaines <br/>             de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. |
| print_large_pdf(file_path, page_settings, printer_settings) | Ouvre et imprime un gros fichier Pdf avec les paramètres de page et d'imprimante spécifiés. Si votre Pdf <br/>             comporte des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour <br/>             obtenir de meilleures performances. |
| print_large_pdf(input_stream, page_settings, printer_settings) | Ouvre et imprime un grand flux Pdf avec les paramètres de page et d'imprimante spécifiés. Si votre fichier Pdf <br/>             contient des centaines de pages ou plus ou que sa taille dépasse 3 Mo, cette méthode est recommandée pour <br/>             obtenir de meilleures performances. |
| print_document_with_settings(page_settings, printer_settings) | Imprime le document Pdf avec les paramètres. Si la taille du document n'est pas compatible avec la taille de la page, pdf.kit l'étendra pour s'adapter à la taille de la page. |
| print_document_with_settings(printer_settings) | Imprime le document Pdf avec les paramètres. Si la taille du document n'est pas compatible avec la taille de la page, pdf.kit l'étendra pour s'adapter à la taille de la page. |
| open_pdf_file(file_path) | Ouvre un fichier Pdf, mais ne décode pas réellement les pages du fichier Pdf. |
| open_pdf_file(input_stream) | Ouvre un flux de fichier Pdf. Mais ne décode pas réellement les pages du fichier Pdf. |
| bind_pdf(src_file) | Initialise la façade. |
| bind_pdf(src_stream) | Initialise la façade. |
| bind_pdf(src_doc) | Initialise la façade. |
| save(dest_file) | Enregistre le document PDF résultant dans un fichier. |
| save(dest_stream) | Enregistre le document PDF résultant dans un flux. |
| decode_all_pages() | Obtient les pages du fichier pdf actuel. |
| decode_page(page_number) | Décode une page d'un fichier Pdf. |
| print_document_with_setup() | Imprime le document Pdf avec une boîte de dialogue de configuration. Choisissez une imprimante à l'aide de la boîte de dialogue. |
| print_document() | Imprime le document Pdf avec une boîte de dialogue de configuration. Choisissez une imprimante à l'aide de la boîte de dialogue. |
| get_default_page_settings() | Obtient les paramètres de page par défaut. |
| get_default_printer_settings() | Obtient les paramètres d'imprimante par défaut. |
| close_pdf_file() | Ferme le fichier Pdf actuel. |
| close() | Ferme le fichier Pdf actuel. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

