---
title: "Classe PdfFileEditor.ContentsResizeParameters"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters. Classe permettant de spécifier les paramètres de redimensionnement de page. Autorise la définition des paramètres suivants : taille de la page résultante (largeur, hauteur) en unités d'espace par défaut ou en pourcentage de la taille des pages initiales, marges gauche, haut, bas et droite en unités d'espace par défaut ou en pourcentage de la taille de la page initiale. Certaines valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après le calcul des valeurs explicitement spécifiées. Par exemple, si la largeur de la page est 100 et que la nouvelle largeur de page spécifiée est 60 unités, les marges gauche et droite sont automatiquement calculées : 100 - 60 / 2 = 15. Cette classe est utilisée dans la méthode ResizeContents."
type: docs
weight: 4600
url: /fr/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

Classe permettant de spécifier les paramètres de redimensionnement de page. Autorise la définition des paramètres suivants : taille de la page résultante (largeur, hauteur) en unités d'espace par défaut ou en pourcentage de la taille des pages initiales ; marges gauche, haut, bas et droite en unités d'espace par défaut ou en pourcentage de la taille de la page initiale ; certaines valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après le calcul des valeurs explicitement spécifiées. Par exemple : si la largeur de la page = 100 et que la nouvelle largeur de page spécifiée est 60 unités, les marges gauche et droite sont automatiquement calculées : (100 - 60) / 2 = 15. Cette classe est utilisée dans la méthode ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Crée des paramètres de redimensionnement où toutes les valeurs sont définies sur "auto". Les marges et la taille du contenu peuvent être spécifiées ultérieurement si nécessaire. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Crée des paramètres de redimensionnement avec des valeurs de marge spécifiées et la taille du contenu. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Obtient ou définit la marge inférieure sur la page résultante. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Obtient ou définit la hauteur du contenu de la page source sur la page résultante. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Obtient ou définit la largeur du contenu de la page source sur la page résultante. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Obtient ou définit la marge gauche sur la page résultante. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Obtient ou définit la marge droite sur la page résultante. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Obtient ou définit la marge supérieure sur la page résultante. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Crée des paramètres de redimensionnement avec la taille de contenu spécifiée. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Crée des paramètres de redimensionnement avec la taille de contenu spécifiée en pourcentage de la taille de la page initiale. Les marges sont calculées automatiquement. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Crée des paramètres de redimensionnement avec la valeur des marges spécifiée. La taille du contenu est calculée automatiquement. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Crée des paramètres de redimensionnement. Les marges sont spécifiées en pourcentage de la taille de la page initiale. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Crée des paramètres de redimensionnement pour le redimensionnement de la page. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Crée des paramètres de redimensionnement pour le redimensionnement de la page. Les nouvelles tailles sont spécifiées en pourcentage. |

### Voir aussi

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


