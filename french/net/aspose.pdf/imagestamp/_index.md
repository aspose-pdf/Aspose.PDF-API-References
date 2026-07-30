---
title: "Classe ImageStamp"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.ImageStamp. Représente un tampon graphique"
type: docs
weight: 6060
url: /fr/net/aspose.pdf/imagestamp/
---
## ImageStamp class

Représente un tampon graphique.

```csharp
public sealed class ImageStamp : Stamp
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Initialise une nouvelle instance de la classe `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Crée un tampon d’image à partir de l’image dans le fichier spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Obtient ou définit le texte alternatif pour le tampon d’image. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Définit ou récupère une valeur booléenne indiquant que le contenu est tamponné en arrière-plan. Si la valeur est vraie, le contenu du tampon est placé en bas. Par défaut, la valeur est fausse, le contenu du tampon est placé en haut. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Obtient ou définit la marge inférieure du tampon. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Obtient ou définit la hauteur de l’image. Définir cette image permet de la mettre à l’échelle verticalement. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Obtient ou définit l'alignement horizontal du tampon sur la page. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Obtient le flux d’image utilisé pour le tamponnage. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Obtient ou définit la marge gauche du tampon. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Obtient ou définit une valeur indiquant l'opacité du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Obtient ou définit une valeur indiquant l'opacité du contour du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Obtient ou définit la valeur de la largeur du contour du tampon. Par défaut, la valeur est 1,0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Obtient ou définit la qualité du tampon d’image en pourcentage. Les valeurs valides sont 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Obtient ou définit la marge droite du tampon. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Définit ou récupère la rotation du contenu du tampon selon les valeurs [`Rotation`](../rotation/). Remarque : cette propriété sert à définir des angles qui sont des multiples de 90 degrés (0, 90, 180, 270 degrés). Pour définir un angle arbitraire, utilisez la propriété RotateAngle. Si l'angle défini par ArbitraryAngle n'est pas un multiple de 90, alors la propriété Rotate renvoie Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Obtient ou définit l'angle de rotation du tampon en degrés. Cette propriété permet de définir un angle de rotation arbitraire. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Obtient ou définit la marge supérieure du tampon. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Obtient ou définit l'alignement vertical du tampon sur la page. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Obtient ou définit la largeur de l’image. Définir cette propriété permet de mettre l’image à l’échelle horizontalement. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Obtient et définit la coordonnée horizontale du tampon, en partant de la gauche. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Obtient et définit la coordonnée verticale du tampon, en partant du bas. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Facteur de zoom du tampon. Permet de mettre à l'échelle le tampon. Veuillez noter que la paire de propriétés ZoomX et ZoomY permet de définir le facteur de zoom pour chaque axe séparément. La définition de cette propriété modifie les propriétés ZoomX et ZoomY. Si ZoomX et ZoomY sont différents, la propriété Zoom renvoie la valeur de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Facteur de zoom horizontal du tampon. Permet de mettre à l'échelle le tampon horizontalement. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Facteur de zoom vertical du tampon. Permet de mettre à l'échelle le tampon verticalement. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Renvoie l'ID du tampon. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Ajoute un tampon graphique sur la page. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Définit l'ID du tampon. |

### Voir aussi

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


