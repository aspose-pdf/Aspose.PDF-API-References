---
title: "ApsSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Options d'enregistrement pour l'exportation au format APS XML."
type: docs
weight: 20
url: /fr/python-net/aspose.pdf/apssaveoptions/
---

## ApsSaveOptions class

Options d'enregistrement pour l'exportation au format APS XML.

Le type ApsSaveOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| ApsSaveOptions() | Initialise une nouvelle instance de la classe ApsSaveOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Rappel pour gérer les avertissements générés. <br/>            Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. <br/>            Continue est l'action par défaut et l'opération d'enregistrement se poursuit, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération d'enregistrement doit s'arrêter. |
| save_format | Format d'enregistrement des données. |
| close_response | Obtient ou définit la valeur booléenne indiquant si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| extract_ocr_sublayer_only | Cet attribut active la fonctionnalité d'extraction d'image ou de texte <br/>            pour les documents PDF avec sous-couche OCR. |
| try_merge_adjacent_same_background_images | Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau)<br/>              construites à partir de plusieurs images d'arrière-plan en mosaïque identiques placées les unes à côté des autres.<br/>              Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois<br/>              des frontières visibles entre les parties des images d'arrière-plan,<br/>              car leurs techniques de lissage des bords d'image (anti-aliasing) diffèrent de celles d'Acrobat Reader.<br/>               Si le document exporté semble contenir de telles frontières visibles entre <br/>              les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous en débarrasser <br/>              de cet effet indésirable. <br/>                ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion,<br/>              donc, veuillez n'utiliser cette option que lorsqu'elle est réellement nécessaire. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

