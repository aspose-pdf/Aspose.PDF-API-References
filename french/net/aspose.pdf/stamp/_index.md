---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Stamp. Une classe abstraite pour divers types de tampons qui viennent comme descendants
type: docs
weight: 10130
url: /fr/net/aspose.pdf/stamp/
---
## Classe Stamp

Une classe abstraite pour divers types de tampons qui viennent comme descendants.

```csharp
public abstract class Stamp
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Définit ou obtient une valeur booléenne qui indique que le contenu est tamponné en tant qu'arrière-plan. Si la valeur est vraie, le contenu du tampon est placé en bas. Par défaut, la valeur est fausse, le contenu du tampon est placé en haut. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Obtient ou définit la marge inférieure du tampon. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Hauteur souhaitée du tampon sur la page. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Obtient ou définit l'alignement horizontal du tampon sur la page. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Obtient ou définit la marge gauche du tampon. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Obtient ou définit une valeur pour indiquer l'opacité du tampon. La valeur est comprise entre 0.0 et 1.0. Par défaut, la valeur est 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Obtient ou définit une valeur pour indiquer l'opacité du contour du tampon. La valeur est comprise entre 0.0 et 1.0. Par défaut, la valeur est 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Obtient ou définit une valeur de la largeur du contour du tampon. Par défaut, la valeur est 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Obtient ou définit la marge droite du tampon. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Définit ou obtient la rotation du contenu du tampon selon les valeurs de [`Rotation`](../rotation/). Remarque. Cette propriété est pour définir des angles qui sont des multiples de 90 degrés (0, 90, 180, 270 degrés). Pour définir un angle arbitraire, utilisez la propriété RotateAngle. Si l'angle défini par ArbitraryAngle n'est pas un multiple de 90, alors la propriété Rotate renvoie Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Obtient ou définit l'angle de rotation du tampon en degrés. Cette propriété permet de définir un angle de rotation arbitraire. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Obtient ou définit la marge supérieure du tampon. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Obtient ou définit l'alignement vertical du tampon sur la page. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Largeur souhaitée du tampon sur la page. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Coordonnée horizontale du tampon, en partant de la gauche. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Coordonnée verticale du tampon, en partant du bas. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Facteur de zoom du tampon. Permet de mettre à l'échelle le tampon. Veuillez noter que la paire de propriétés ZoomX et ZoomY permet de définir le facteur de zoom pour chaque axe séparément. La définition de cette propriété modifie à la fois les propriétés ZoomX et ZoomY. Si ZoomX et ZoomY sont différents, alors la propriété Zoom renvoie la valeur de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Facteur de zoom horizontal du tampon. Permet de mettre à l'échelle le tampon horizontalement. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Facteur de zoom vertical du tampon. Permet de mettre à l'échelle le tampon verticalement. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Renvoie l'ID du tampon. |
| abstract [Put](../../aspose.pdf/stamp/put/)(Page) | Ajoute un tampon sur la page. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Définit l'ID du tampon. |

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)