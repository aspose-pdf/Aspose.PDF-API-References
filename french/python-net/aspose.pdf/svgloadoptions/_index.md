---
title: "SvgLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente les options de chargement/importation d'un fichier SVG dans un document PDF."
type: docs
weight: 1450
url: /fr/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

Représente les options de chargement/importation d'un fichier SVG dans un document PDF.

Le type SvgLoadOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| SvgLoadOptions() | Initialise une nouvelle instance de la classe SvgLoadOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Rappel pour gérer les avertissements générés. <br/>            Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. <br/>            Continue est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération de chargement doit s'arrêter. |
| load_format | Représente le format de fichier décrit par [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| page_info | Obtient ou définit les informations de page qui doivent être appliquées lors du chargement du document.<br/>            NOTE que ce paramètre ne fonctionne que lorsque ConversionEngine == ConversionEngines.NewEngine |
| adjust_page_size | Ajuste la taille de la page PDF à la taille du SVG |
| conversion_engine | Permet de sélectionner le moteur de conversion qui sera utilisé pendant la conversion.<br/>            Actuellement le nouveau moteur est en phase de test B, donc cette valeur est définie par défaut à <br/>            ConversionEngines.LegacyEngine |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

