---
title: "XslFoLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente les options de chargement/importation du fichier XSL-FO dans le document pdf."
type: docs
weight: 1820
url: /fr/python-net/aspose.pdf/xslfoloadoptions/
---

## XslFoLoadOptions class

Représente les options de chargement/importation du fichier XSL-FO dans le document pdf.

Le type XslFoLoadOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| XslFoLoadOptions() | Crée l'objet [XslFoLoadOptions](/pdf/python-net/aspose.pdf/xslfoloadoptions/) sans données xsl. |
| XslFoLoadOptions(xsl_file) | Initialise une nouvelle instance de la classe XslFoLoadOptions |
| XslFoLoadOptions(xsl_stream) | Initialise une nouvelle instance de la classe XslFoLoadOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Rappel pour gérer les avertissements générés. <br/>            Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. <br/>            Continue est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération de chargement doit s'arrêter. |
| load_format | Représente le format de fichier décrit par [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| xsl_stream | Obtient les données xsl pour convertir le xml en document pdf. |
| base_path | Le chemin/base URL à partir duquel sont recherchés les chemins relatifs vers les ressources externes (le cas échéant) référencées dans le fichier SVG chargé. |
| parsing_errors_handling_type | Le document source XSLFO peut contenir des erreurs de formatage. Cette énumération énumère les stratégies possibles de gestion de ces erreurs |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

