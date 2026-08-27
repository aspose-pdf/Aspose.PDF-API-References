---
title: "DocSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Options d'enregistrement pour l'exportation au format Doc"
type: docs
weight: 220
url: /fr/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Options d'enregistrement pour l'exportation au format Doc

Le type DocSaveOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| DocSaveOptions() | Initialise une nouvelle instance de la classe DocSaveOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Rappel pour gérer les avertissements générés. <br/>            Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. <br/>            Continue est l'action par défaut et l'opération d'enregistrement se poursuit, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération d'enregistrement doit s'arrêter. |
| save_format | Format d'enregistrement des données. |
| close_response | Obtient ou définit la valeur booléenne indiquant si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| extract_ocr_sublayer_only | Cet attribut active la fonctionnalité d'extraction d'image ou de texte <br/>            pour les documents PDF avec sous-couche OCR. |
| try_merge_adjacent_same_background_images | Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau)<br/>              construites à partir de plusieurs images d'arrière-plan en mosaïque identiques placées les unes à côté des autres.<br/>              Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois<br/>              des frontières visibles entre les parties des images d'arrière-plan,<br/>              car leurs techniques de lissage des bords d'image (anti-aliasing) diffèrent de celles d'Acrobat Reader.<br/>               Si le document exporté semble contenir de telles frontières visibles entre <br/>              les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous en débarrasser <br/>              de cet effet indésirable. <br/>                ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion,<br/>              donc, veuillez n'utiliser cette option que lorsqu'elle est réellement nécessaire. |
| mode | Mode de reconnaissance. |
| relative_horizontal_proximity | Dans les PDF, les mots peuvent être représentés en interne par des opérateurs qui impriment les mots<br/>              en imprimant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter les mots, il faut parfois détecter des groupes<br/>              de caractères indépendants qui sont en fait des mots.<br/>                Ce paramètre définit la largeur de l'espace entre les éléments de texte (lettres, syllabes) <br/>              qui doit être considéré comme la distance entre les mots lors de la reconnaissance des mots dans le PDF source.<br/>              (la présence d'un espace vide d'au moins cette largeur entre les lettres signifie que <br/>               les éléments textuels appartiennent à des mots différents).<br/>              Il est normalisé à la taille de police – 1,0 signifie 100 % de la taille de police supposée du mot.<br/>             ATTENTION ! Il n'est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées<br/>             pour lesquelles la valeur optimale ne peut pas être calculée à partir de la police. <br/>               Ainsi, dans la grande majorité des cas, ce paramètre ne modifie rien dans le document résultant. |
| max_distance_between_text_lines | Ce paramètre est utilisé pour regrouper les lignes de texte en paragraphes.<br/>            Détermine à quelle distance peuvent être deux lignes de texte relatives. Spécifié en centaines de pourcentage de la hauteur des lignes de texte. |
| recognize_bullets | Activer la reconnaissance des puces |
| add_return_to_line_end | Utiliser les sauts de paragraphe ou de ligne |
| image_resolution_x | Résolution X des images converties. |
| image_resolution_y | Résolution Y des images converties. |
| format | Format de sortie |
| batch_size | Définit la taille du lot si la conversion par lots est applicable<br/>            à la paire de formats source et destination. |
| memory_save_mode_path | Définit le chemin (nom de fichier ou nom de répertoire) pour stocker<br/>            les données temporaires lors de la conversion en mode d'enregistrement en mémoire. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

