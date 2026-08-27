---
title: "LatexLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente les options de chargement/importation d'un fichier TeX dans un document PDF."
type: docs
weight: 820
url: /fr/python-net/aspose.pdf/latexloadoptions/
---

## LatexLoadOptions class

Représente les options de chargement/importation d'un fichier TeX dans un document PDF.

Le type LatexLoadOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| LatexLoadOptions() | Initialise une nouvelle instance de la classe LatexLoadOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Rappel pour gérer les avertissements générés. <br/>            Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. <br/>            Continue est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération de chargement doit s'arrêter. |
| load_format | Représente le format de fichier décrit par [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| job_name | Obtient/definit le nom du job. |
| input_directory | Obtient/definit le répertoire d'entrée TeX. |
| output_directory | Obtient/definit le répertoire de sortie TeX. |
| repeat | Obtient/definit le drapeau indiquant s'il est nécessaire d'exécuter le travail TeX deux fois dans le cas,<br/>            par exemple, il y a des références dans le(s) fichier(s) TeX d'entrée. En général, ce comportement est utile lorsque<br/>            le moteur collecte certaines données pendant le processus de composition et les stocke dans un fichier auxiliaire,<br/>            lors de la première exécution. Et lors de la deuxième exécution, le moteur utilise d'une manière ou d'une autre ces données. |
| subset_fonts | Obtient/definit le drapeau indiquant s'il faut sous-ensemble les polices dans le fichier de sortie ou non. |
| show_terminal_output | Obtient/definit le drapeau indiquant s'il faut afficher la sortie du terminal sur la console. |
| date_time | Obtient/definit une certaine valeur pour les primitives date/heure comme \year, \month, \day et \time. |
| no_ligatures | Obtient/definit un drapeau qui annule les ligatures dans toutes les polices. |
| rasterize_formulas | Obtient/definit un drapeau qui permet de rasteriser les formules mathématiques. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

