---
title: "EpubSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Options d'enregistrement pour l'exportation au format EPUB"
type: docs
weight: 320
url: /fr/python-net/aspose.pdf/epubsaveoptions/
---

## EpubSaveOptions class

Options d'enregistrement pour l'exportation au format EPUB

Le type EpubSaveOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| EpubSaveOptions() | Initialise une nouvelle instance de la classe EpubSaveOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Rappel pour gérer les avertissements générés. <br/>            Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. <br/>            Continue est l'action par défaut et l'opération d'enregistrement se poursuit, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération d'enregistrement doit s'arrêter. |
| save_format | Format d'enregistrement des données. |
| close_response | Obtient ou définit la valeur booléenne indiquant si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| extract_ocr_sublayer_only | Cet attribut active la fonctionnalité d'extraction d'image ou de texte <br/>            pour les documents PDF avec sous-couche OCR. |
| try_merge_adjacent_same_background_images | Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau)<br/>              construites à partir de plusieurs images d'arrière-plan en mosaïque identiques placées les unes à côté des autres.<br/>              Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois<br/>              des frontières visibles entre les parties des images d'arrière-plan,<br/>              car leurs techniques de lissage des bords d'image (anti-aliasing) diffèrent de celles d'Acrobat Reader.<br/>               Si le document exporté semble contenir de telles frontières visibles entre <br/>              les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous en débarrasser <br/>              de cet effet indésirable. <br/>                ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion,<br/>              donc, veuillez n'utiliser cette option que lorsqu'elle est réellement nécessaire. |
| content_recognition_mode | Lorsque le fichier PDF (qui a généralement une mise en page fixe) est converti,<br/>            le moteur de conversion tente d'effectuer un regroupement et une analyse à plusieurs niveaux pour restaurer<br/>            l'intention de l'auteur du document original et produire un résultat en mise en page fluide.<br/>               Cette propriété ajuste cette conversion pour telle ou telle<br/>            méthode souhaitable de reconnaissance du contenu. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

