---
title: "SvgSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Options d'enregistrement pour l'exportation au format SVG"
type: docs
weight: 1460
url: /fr/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

Options d'enregistrement pour l'exportation au format SVG

Le type SvgSaveOptions expose les membres suivants:
## Constructeurs
| Nom | Description |
| :- | :- |
| SvgSaveOptions() | Initialise une nouvelle instance de la classe SvgSaveOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Rappel pour gérer les avertissements générés. <br/>            Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. <br/>            Continue est l'action par défaut et l'opération d'enregistrement se poursuit, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération d'enregistrement doit s'arrêter. |
| save_format | Format d'enregistrement des données. |
| close_response | Obtient ou définit la valeur booléenne indiquant si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| extract_ocr_sublayer_only | Aucun |
| try_merge_adjacent_same_background_images | Aucun |
| treat_target_file_name_as_directory | Cette option définit si un répertoire cible sera créé<br/>             (s’il n’existe pas encore) avec le même nom que le fichier de sortie demandé <br/>             au lieu du fichier de sortie lui‑-même.<br/>             Ainsi, ce répertoire contiendra toutes les images SVG de sortie des pages (comme décrit ci‑dessous).<br/>               Si non, les fichiers de sortie des pages autres que la première seront créés exactement dans le répertoire demandé<br/>            en tant que fichier de sortie principal, mais le nom de fichier comportera le suffixe _[2...n], qui<br/>             est défini par le numéro de page, par ex. si vous définissez le fichier de sortie "C:\\AsposeTests\\output.svg"<br/>             et que la sortie contient plusieurs fichiers svg de pages,<br/>             alors les fichiers des pages seront également créés dans le répertoire "C:\\AsposeTests\\" et auront les noms 'output.svg', 'output_2.svg', 'output_3.svg' etc. |
| compress_output_to_zip_archive | Spécifie si la sortie sera créée sous forme d’une archive zip.<br/>             Veuillez vous référer au commentaire des options 'TreatTargetFileNameAsDirectory' pour voir les règles de nommage<br/>             des fichiers svg des pages pour un document source multipage, qui sont également appliquées à l’ensemble zip des fichiers de sortie. |
| scale_to_pixels | Spécifie s’il faut mettre à l’échelle le document de sortie des points typographiques aux pixels. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

