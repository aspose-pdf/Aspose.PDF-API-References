---
title: "LaTeXSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Options d'enregistrement pour l'exportation au format TeX."
type: docs
weight: 800
url: /fr/python-net/aspose.pdf/latexsaveoptions/
---

## LaTeXSaveOptions class

Options d'enregistrement pour l'exportation au format TeX.

Le type LaTeXSaveOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| LaTeXSaveOptions() | Initialise une nouvelle instance de la classe LaTeXSaveOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Aucun |
| save_format | Aucun |
| close_response | Aucun |
| extract_ocr_sublayer_only | Cet attribut active la fonctionnalité d'extraction d'image ou de texte <br/>            pour les documents PDF avec sous-couche OCR. |
| try_merge_adjacent_same_background_images | Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau)<br/>              construites à partir de plusieurs images d'arrière-plan en mosaïque identiques placées les unes à côté des autres.<br/>              Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois<br/>              des frontières visibles entre les parties des images d'arrière-plan,<br/>              car leurs techniques de lissage des bords d'image (anti-aliasing) diffèrent de celles d'Acrobat Reader.<br/>               Si le document exporté semble contenir de telles frontières visibles entre <br/>              les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous en débarrasser <br/>              de cet effet indésirable. <br/>                ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion,<br/>              donc, veuillez n'utiliser cette option que lorsqu'elle est réellement nécessaire. |
| out_directory_path | Propriété pour |
| pages_count | Renvoie le nombre de pages après la conversion. |
## Méthodes
| Nom | Description |
| :- | :- |
| add_font_encs(font_encs) | Ajoute un encodage de police à la liste des encodages de police |
| clear_font_encs() | Efface la liste d'encodage des polices |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

