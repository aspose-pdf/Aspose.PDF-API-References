---
title: "HtmlLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente les options de chargement/importation d'un fichier html dans un document pdf."
type: docs
weight: 480
url: /fr/python-net/aspose.pdf/htmlloadoptions/
---

## HtmlLoadOptions class

Représente les options de chargement/importation d'un fichier html dans un document pdf.

Le type HtmlLoadOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| HtmlLoadOptions() | Crée des options de chargement pour convertir du html en document pdf avec un chemin de base vide. |
| HtmlLoadOptions(base_path) | Initialise une nouvelle instance de la classe HtmlLoadOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Rappel pour gérer les avertissements générés. <br/>            Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. <br/>            Continue est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération de chargement doit s'arrêter. |
| load_format | Représente le format de fichier décrit par [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| is_render_to_single_page | Obtient ou définit le rendu de tout le document sur une seule page |
| is_embed_fonts | Obtient ou définit l'incorporation des polices dans le document résultant |
| page_layout_option | Obtient ou définit l'option de mise en page. |
| html_media_type | Obtient ou définit les types de médias possibles utilisés lors du rendu. |
| input_encoding | Obtient ou définit l'attribut spécifiant l'encodage utilisé pour ce document au moment de l'analyse. Si cet attribut est nul, l'encodage sera déterminé à partir de l'attribut du jeu de caractères du document. |
| base_path | Le chemin/base URL du fichier html. |
| page_info | Obtient ou définit les informations de la page du document |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

