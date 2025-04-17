---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters. Classe pour spécifier les paramètres de redimensionnement de page. Permet de définir les paramètres suivants  Taille de la page résultante en unités d'espace par défaut ou en pourcentages de la taille des pages initiales ; Marges gauche, supérieure, inférieure et droite en unités d'espace par défaut ou en pourcentages de la taille de la page initiale ; Certains valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après le calcul des valeurs explicitement spécifiées. Cette classe est utilisée dans la méthode ResizeContents.
type: docs
weight: 4480
url: /fr/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## Classe PdfFileEditor.ContentsResizeParameters

Classe pour spécifier les paramètres de redimensionnement de page. Permet de définir les paramètres suivants : Taille de la page résultante (largeur, hauteur) en unités d'espace par défaut ou en pourcentages de la taille des pages initiales ; Marges gauche, supérieure, inférieure et droite en unités d'espace par défaut ou en pourcentages de la taille de la page initiale ; Certaines valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après le calcul des valeurs explicitement spécifiées. Par exemple : si la largeur de la page = 100 et la nouvelle largeur de la page spécifiée est de 60 unités, alors les marges gauche et droite sont automatiquement calculées : (100 - 60) / 2 = 15. Cette classe est utilisée dans la méthode ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Crée des paramètres de redimensionnement où toutes les valeurs sont définies sur "auto". Plus tard, les marges et la taille du contenu peuvent être spécifiées si nécessaire. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Crée des paramètres de redimensionnement avec des valeurs de marges spécifiées et une taille de contenu. |

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
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Crée des paramètres de redimensionnement avec une taille de contenu spécifiée. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Crée des paramètres de redimensionnement avec une taille de contenu spécifiée en pourcentages de la taille de la page initiale. Les marges sont calculées automatiquement. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Crée des paramètres de redimensionnement avec des valeurs de marges spécifiées. La taille du contenu est calculée automatiquement. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Crée des paramètres de redimensionnement. Les marges sont spécifiées en pourcentages de la taille de la page initiale. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Crée des paramètres de redimensionnement pour le redimensionnement de page. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Crée des paramètres de redimensionnement pour le redimensionnement de page. Les nouvelles tailles sont spécifiées en pourcentage. |

### Voir aussi

* classe [PdfFileEditor](../pdffileeditor/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)