---
title: PdfPageStamp
second_title: Référence de l'API Aspose.PDF pour .NET
description: La classe représente le tampon qui utilise la page PDF comme tampon.
type: docs
weight: 6070
url: /fr/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

La classe représente le tampon qui utilise la page PDF comme tampon.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfPageStamp](pdfpagestamp#constructor)(Page) | Constructeur de PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp#constructor_1)(Stream, int) | Crée un tampon de page PDF à partir de la page spécifiée dans le document à partir du flux. |
| [PdfPageStamp](pdfpagestamp#constructor_2)(string, int) | Crée un tampon de page PDF à partir de la page spécifiée du document dans le fichier spécifié. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Définit ou obtient une valeur booléenne qui indique que le contenu est tamponné en arrière-plan. Si la valeur est true, le contenu du tampon est posé en bas. Par défaut, la valeur est false, le contenu du tampon est posé en haut. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Obtient ou définit la marge inférieure du tampon. |
| virtual [Height](../../aspose.pdf/stamp/height) { get; set; } | Hauteur souhaitée du tampon sur la page. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Obtient ou définit l'alignement horizontal du tampon sur la page. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Obtient ou définit la marge gauche du tampon. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Obtient ou définit une valeur pour indiquer l'opacité du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Obtient ou définit une valeur pour indiquer l'opacité du contour du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Obtient ou définit une valeur de la largeur du contour du tampon. Par défaut, la valeur est 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage) { get; set; } | Obtient ou définit la page qui sera utilisée comme tampon. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Obtient ou définit la marge droite du tampon. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Définit ou obtient la rotation du contenu du tampon en fonction[`Rotation`](../rotation) valeurs. Remarque. Cette propriété concerne les angles définis qui sont des multiples de 90 degrés (0, 90, 180, 270 degrés). Pour définir un angle arbitraire, utilisez la propriété RotateAngle. Si l'angle défini par ArbitraryAngle n'est pas multiple de 90, la propriété Rotate renvoie Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Obtient ou définit l'angle de rotation du tampon en degrés. Cette propriété permet de définir un angle de rotation arbitraire. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Obtient ou définit la marge supérieure du tampon. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Obtient ou définit l'alignement vertical du tampon sur la page. |
| virtual [Width](../../aspose.pdf/stamp/width) { get; set; } | Largeur souhaitée du tampon sur la page. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Coordonnée horizontale du tampon, en partant de la gauche. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Coordonnée verticale du tampon, en partant du bas. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Facteur de zoom du tampon. Permet de mettre à l'échelle le tampon. Veuillez noter que la paire de propriétés ZoomX et ZoomY permet de définir le facteur de zoom pour chaque axe séparément. La définition de cette propriété modifie les propriétés ZoomX et ZoomY. Si ZoomX et ZoomY sont différents, la propriété Zoom renvoie la valeur ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Facteur de zoom horizontal du tampon. Permet de redimensionner le tampon horizontalement. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Facteur de zoom vertical du tampon. Permet de redimensionner le tampon verticalement. |

## Méthodes

| Nom | La description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Renvoie l'ID du tampon. |
| override [Put](../../aspose.pdf/pdfpagestamp/put)(Page) | Mettre un tampon sur la page spécifiée. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Définit l'ID de tampon. |

### Voir également

* class [Stamp](../stamp)
* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
