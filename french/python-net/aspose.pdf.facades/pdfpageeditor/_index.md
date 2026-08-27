---
title: "PdfPageEditor"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe permettant de modifier la page d'un fichier PDF, y compris la rotation de la page, le zoom, le déplacement et la modification de la taille de la page."
type: docs
weight: 340
url: /fr/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

Représente une classe permettant de modifier la page d'un fichier PDF, y compris la rotation de la page, le zoom, le déplacement et la modification de la taille de la page.

Le type PdfPageEditor expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfPageEditor() | Constructeur de la classe PdfPageEditor. |
| PdfPageEditor(document) | Initialise une nouvelle instance de la classe PdfPageEditor |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| transition_duration | Obtient ou définit la durée de l'effet de transition. |
| transition_type | Obtient ou définit le style de transition à utiliser lors du passage à cette page depuis une autre pendant une présentation. |
| display_duration | Obtient ou définit la durée d'affichage des pages. |
| process_pages | Obtient ou définit les numéros de page à éditer. Par défaut, chaque page serait éditée. |
| rotation | Obtient ou définit la rotation des pages, la rotation doit être 0, 90, 180 ou 270.<br/>            Valeur par défaut : 0. |
| zoom | Obtient ou définit le coefficient de zoom. La valeur 1,0 correspond à 100 %.<br/>            La valeur par défaut est 1,0. |
| page_size | Obtient ou définit la taille de page du fichier de sortie. |
| alignement | Obtient ou définit l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left. |
| horizontal_alignment | Obtient ou définit l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left. |
| vertical_alignment | Obtient ou définit l'alignement vertical du contenu PDF original sur la page résultante, la valeur par défaut est VerticalAlignmentType.Bottom. |
| vertical_alignment_type | Obtient ou définit l'alignement vertical du contenu PDF original sur la page résultante, la valeur par défaut est VerticalAlignmentType.Bottom. |
| SPLITVOUT | Division verticale de sortie |
| SPLITHOUT | Division horizontale de sortie |
| SPLITVIN | Division verticale d'entrée |
| SPLITHIN | Division horizontale d'entrée |
| BLINDV | Persiennes verticales |
| BLINDH | Persiennes verticales |
| INBOX | Boîte intérieure |
| OUTBOX | Boîte extérieure |
| LRWIPE | Balayage gauche-droite |
| RLWIPE | Balayage droite-gauche |
| BTWIPE | Essuyage du bas vers le haut |
| TBWIPE | Essuyage du haut vers le bas |
| DISSOLVE | L'ancienne page se dissout |
| LRGLITTER | Scintillement de gauche à droite |
| TBGLITTER | Scintillement du haut vers le bas |
| DGLITTER | Scintillement diagonal |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(src_file) | Lie le document PDF pour l'édition. |
| bind_pdf(src_stream) | Lie le document PDF pour l'édition. |
| bind_pdf(src_doc) | Lie le document PDF pour l'édition. |
| save(output_file) | Enregistre le document modifié dans un fichier. |
| save(output_stream) | Enregistre le document modifié dans le flux. |
| close() | Libère toutes les ressources associées à la façade actuelle. |
| move_position(move_x, move_y) | Déplace l'origine de (0, 0) vers le point indiqué. <br/>            L'origine est en bas à gauche et l'unité est le point (1 pouce = 72 points). |
| get_pages() | Renvoie le nombre total de pages. |
| get_page_size(page) | Renvoie la taille de la page spécifiée. |
| get_page_rotation(page) | Renvoie la rotation de la page spécifiée. |
| get_page_box_size(page, page_box_name) | Renvoie la taille de la boîte spécifiée dans le document. |
| apply_changes() | Applique les modifications apportées aux pages du document. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

