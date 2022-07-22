---
title: PdfFileEditor.ContentsResizeParameters
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe pour spécifier les paramètres de redimensionnement de la page. Permet de définir les paramètres suivants  Taille de la page de résultat largeur hauteur en unités despace par défaut ou en pourcentage de la taille initiale des pages  Marges de gauche du haut du bas et de droite dans les unités despace par défaut ou en pourcentage de la taille de page initiale  Certaines valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après calcul des valeurs explicitement spécifiées. Par exemple  si la largeur de la page  100 et la nouvelle largeur de page spécifiée 60 unités alors les marges gauche et droite sont automatiquement calculées  100 - 60 / 2  15. Cette classe est utilisée dans la méthode ResizeContents.
type: docs
weight: 2490
url: /fr/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

Classe pour spécifier les paramètres de redimensionnement de la page. Permet de définir les paramètres suivants : Taille de la page de résultat (largeur, hauteur) en unités d'espace par défaut ou en pourcentage de la taille initiale des pages ; Marges de gauche, du haut, du bas et de droite dans les unités d'espace par défaut ou en pourcentage de la taille de page initiale ; Certaines valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après calcul des valeurs explicitement spécifiées. Par exemple : si la largeur de la page = 100 et la nouvelle largeur de page spécifiée 60 unités, alors les marges gauche et droite sont automatiquement calculées : (100 - 60) / 2 = 15. Cette classe est utilisée dans la méthode ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ContentsResizeParameters](contentsresizeparameters#constructor)() | Crée des paramètres de redimensionnement où toutes les valeurs sont définies sur "auto". Les marges ultérieures et la taille du contenu peuvent être spécifiées si nécessaire. |
| [ContentsResizeParameters](contentsresizeparameters#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Crée des paramètres de redimensionnement avec des valeurs de marge et une taille de contenu spécifiées. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/contentsresizeparameters/bottommargin) { get; set; } | Obtient ou définit la marge inférieure sur la page résultante. |
| [ContentsHeight](../../aspose.pdf.facades/contentsresizeparameters/contentsheight) { get; set; } | Obtient ou définit la hauteur du contenu de la page source sur la page résultante. |
| [ContentsWidth](../../aspose.pdf.facades/contentsresizeparameters/contentswidth) { get; set; } | Obtient ou définit la largeur du contenu de la page source sur la page résultante. |
| [LeftMargin](../../aspose.pdf.facades/contentsresizeparameters/leftmargin) { get; set; } | Obtient ou définit la marge gauche sur la page résultante. |
| [RightMargin](../../aspose.pdf.facades/contentsresizeparameters/rightmargin) { get; set; } | Obtient ou définit la marge droite sur la page résultante. |
| [TopMargin](../../aspose.pdf.facades/contentsresizeparameters/topmargin) { get; set; } | Obtient ou définit la marge supérieure sur la page résultante. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/contentsresizeparameters/contentsize)(double, double) | Crée des paramètres de redimensionnement avec la taille de contenu spécifiée. |
| static [ContentSizePercent](../../aspose.pdf.facades/contentsresizeparameters/contentsizepercent)(double, double) | Crée des paramètres de redimensionnement avec une taille de contenu spécifiée en pourcentage de la taille de page initiale. Les marges sont calculées automatiquement. |
| static [Margins](../../aspose.pdf.facades/contentsresizeparameters/margins)(double, double, double, double) | Crée des paramètres de redimensionnement avec une valeur de marge spécifiée. La taille du contenu est calculée automatiquement. |
| static [MarginsPercent](../../aspose.pdf.facades/contentsresizeparameters/marginspercent)(double, double, double, double) | Crée des paramètres de redimensionnement. Les marges sont spécifiées en pourcentage de la taille de page initiale. |
| static [PageResize](../../aspose.pdf.facades/contentsresizeparameters/pageresize)(double, double) | Crée des paramètres de redimensionnement pour le redimensionnement de la page. |
| static [PageResizePct](../../aspose.pdf.facades/contentsresizeparameters/pageresizepct)(double, double) | Crée des paramètres de redimensionnement pour le redimensionnement de la page. Les nouvelles tailles sont spécifiées en pourcentage. |

### Voir également

* class [PdfFileEditor](../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
