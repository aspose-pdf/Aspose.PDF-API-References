---
title: "PdfSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Options d'enregistrement pour l'exportation au format PDF"
type: docs
weight: 1240
url: /fr/python-net/aspose.pdf/pdfsaveoptions/
---

## PdfSaveOptions class

Options d'enregistrement pour l'exportation au format PDF

Le type PdfSaveOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfSaveOptions() | Initialise une nouvelle instance de la classe PdfSaveOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Rappel pour gérer les avertissements générés. <br/>            Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. <br/>            Continue est l'action par défaut et l'opération d'enregistrement se poursuit, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération d'enregistrement doit s'arrêter. |
| save_format | Format d'enregistrement des données. |
| close_response | Obtient ou définit la valeur booléenne indiquant si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| temp_path | Chemin pour les fichiers temporaires. |
| default_font_name | Nom de police utilisé par défaut pour les polices qui sont absentes sur l'ordinateur.<br/>            Lorsque le document PDF qui est enregistré contient des polices qui ne sont pas disponibles <br/>            dans le document lui‑-même et sur l'appareil, l'API remplace ces polices par la <br/>            police par défaut (si une police avec [default_font_name](/pdf/python-net/aspose.pdf/pdfsaveoptions/) est trouvée sur l'appareil) |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

