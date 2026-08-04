---
title: "PdfConverter"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe permettant de convertir chaque page d'un fichier pdf en images, prenant désormais en charge BMP, JPEG, PNG et TIFF.<br/>            Contenu pris en charge dans les pdfs : images, formulaires, commentaires."
type: docs
weight: 200
url: /fr/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

Représente une classe permettant de convertir chaque page d'un fichier pdf en images, prenant désormais en charge BMP, JPEG, PNG et TIFF.<br/>            Contenu pris en charge dans les pdf : images, formulaires, commentaires.

Le type PdfConverter expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfConverter() | Initialise un nouvel objet [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/). |
| PdfConverter(document) | Initialise une nouvelle instance de la classe PdfConverter |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| coordinate_type | Obtient ou définit le type de coordonnées de la page (Media/Crop boxes). La valeur CropBox est utilisée par défaut. |
| show_hidden_areas | Obtient ou définit le drapeau qui contrôle la visibilité des zones cachées sur la page. |
| rendering_options | Obtient ou définit les options de rendu. |
| form_presentation_mode | Obtient ou définit le mode de présentation du formulaire. |
| resolution | Obtient ou définit la résolution lors de la conversion. Plus la résolution est élevée, plus la vitesse de conversion est lente. La valeur par défaut est 150. |
| start_page | Obtient ou définit la position de départ que vous souhaitez convertir. La valeur minimale est 1. |
| end_page | Obtient ou définit la position de fin que vous souhaitez convertir. |
| password | Obtient ou définit le OwnerPassword du document. |
| user_password | Obtient ou définit le UserPassword du document. |
| page_count | Obtient le nombre de pages. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(input_file) | Lie un fichier Pdf pour la conversion. |
| bind_pdf(input_stream) | Lie un flux Pdf pour la conversion. |
| bind_pdf(src_doc) | Initialise la façade. |
| save_as_tiff(output_file) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_file, compression_type) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_file, image_width, image_height) | Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_file, page_size) | Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_file, page_size, settings) | Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_file, image_width, image_height, settings) | Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_stream) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| save_as_tiff(output_stream, compression_type) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_stream, page_size) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| save_as_tiff(output_stream, page_size, settings) | Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul flux TIFF. |
| save_as_tiff(output_stream, image_width, image_height) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul flux TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings) | Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul flux TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul flux TIFF. |
| save_as_tiff(output_file, settings) | Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_file, settings, converter) | Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul fichier TIFF. |
| save_as_tiff(output_stream, settings) | Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul flux TIFF. |
| save_as_tiff(output_stream, settings, converter) | Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul flux TIFF. |
| save_as_tiff_class_f(output_file, image_width, image_height) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. |
| save_as_tiff_class_f(output_file, page_size) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| save_as_tiff_class_f(output_stream, page_size) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| save_as_tiff_class_f(output_file) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. |
| save_as_tiff_class_f(output_stream) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| get_next_image(output_file) | Enregistre l'image dans un fichier avec le format d'image par défaut - jpeg. |
| get_next_image(output_file, page_size) | Enregistre l'image dans un fichier avec la taille de page donnée i-ème et le format d'image par défaut - jpeg. |
| get_next_image(output_file, format) | Enregistre l'image dans un fichier avec le format d'image fourni. |
| get_next_image(output_file, page_size, format) | Enregistre l'image dans un fichier avec la taille de page et le format d'image donnés. |
| get_next_image(output_stream) | Enregistre l'image dans le flux avec le format d'image par défaut - jpeg. |
| get_next_image(output_stream, page_size) | Enregistre l'image dans le flux avec la taille de page donnée. |
| get_next_image(output_stream, format) | Enregistre l'image dans le flux avec le format d'image donné. |
| get_next_image(output_stream, page_size, format) | Enregistre l'image dans le flux avec la taille de page donnée. |
| get_next_image(output_file, format, image_width, image_height, quality) | Enregistre l'image dans le fichier avec le format d'image donné, les dimensions et la qualité. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Enregistre l'image dans le flux avec le format d'image donné, les dimensions et la qualité. |
| get_next_image(output_file, format, image_width, image_height, quality) | Enregistre l'image dans le fichier avec le format d'image donné, la taille de l'image et la qualité. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Enregistre l'image dans le flux avec le format d'image donné, la taille et la qualité. |
| get_next_image(output_file, format, image_width, image_height) | Enregistre l'image dans le fichier avec le format d'image donné, les dimensions et la qualité. |
| get_next_image(output_stream, format, image_width, image_height) | Enregistre l'image dans le flux avec le format d'image donné, les dimensions et la qualité. |
| get_next_image(output_stream, format, quality) | Enregistre l'image dans le flux avec le format d'image donné, les dimensions et la qualité. |
| get_next_image(output_stream, page_size, format, quality) | Enregistre l'image dans le flux avec la taille de page donnée, le format d'image et la qualité. |
| get_next_image(output_file, format, quality) | Enregistre l'image dans le fichier avec le format d'image donné, les dimensions et la qualité. |
| get_next_image(output_file, page_size, format, quality) | Enregistre l'image dans le fichier avec la taille de page donnée, le format d'image et la qualité. |
| close() | Fermez l'instance de PdfConverter et libérez les ressources. |
| do_convert() | Effectuez quelques travaux initiaux pour convertir un document pdf en images. |
| has_next_image() | Indique si le fichier pdf contient plus d'images ou non. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | Aucun |
| merge_images_as_tiff(input_images_streams) | Fusionne la liste des flux tiff en un seul flux tiff à plusieurs images. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

