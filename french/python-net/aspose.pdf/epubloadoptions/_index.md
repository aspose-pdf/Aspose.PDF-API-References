---
title: "EpubLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Contient des options pour le chargement/l'importation d'un fichier EPUB dans le document PDF."
type: docs
weight: 310
url: /fr/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

Contient des options pour le chargement/l'importation d'un fichier EPUB dans le document PDF.

Le type EpubLoadOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| EpubLoadOptions() | Crée les options de chargement par défaut pour convertir un fichier EPUB en document PDF. <br/>            Taille de page PDF par défaut - A4 300dpi 2480 X 3508. |
| EpubLoadOptions(page_size) | Initialise une nouvelle instance de la classe EpubLoadOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| warning_handler | Rappel pour gérer les avertissements générés. <br/>            Le WarningHandler renvoie l'élément d'énumération ReturnAction spécifiant soit Continue, soit Abort. <br/>            Continue est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également renvoyer Abort, auquel cas l'opération de chargement doit s'arrêter. |
| load_format | Représente le format de fichier décrit par [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| page_size | Obtient ou définit la taille de page de sortie pour l'importation. |
| marge | Obtient une référence sur l'objet qui représente les informations de marge. |
| margins_area_usage_mode | Représente le mode d'utilisation de la zone des marges - définit le traitement <br/>              des instructions (le cas échéant) du CSS du document importé<br/>              liées à l'utilisation des marges. |
| page_size_adjustment_mode | ATTENTION! La fonctionnalité est implémentée mais n'est pas encore exposée dans l'API publique en raison d'un problème bloquant dans la couche <br/>              OSHARED découvert pour le document d'exemple.<br/>              <br/>             <br/>              Représente le mode d'utilisation de la taille de page lors de la conversion.<br/>             Les formats (comme HTML, EPUB, etc.) ont généralement une mise en page fluide, ce qui permet d'adapter la taille de page requise.<br/>             Cependant, parfois le contenu possède des positions horizontales ou une taille spécifiées qui <br/>             n'autorisent pas le placement du contenu dans la taille de page requise.<br/>               Dans ce cas, nous pouvons définir ce qui doit être fait (c'est‑à‑dire lorsque la taille du contenu ne correspond pas <br/>             à la taille de page initiale requise du document PDF résultant). |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

