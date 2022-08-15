---
title: PageNumberStamp
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente le tampon du numéro de page et sert à numéroter les pages.
type: docs
weight: 5890
url: /fr/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

Représente le tampon du numéro de page et sert à numéroter les pages.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PageNumberStamp](pagenumberstamp#constructor)() | Initialise une nouvelle instance du[`PageNumberStamp`](../pagenumberstamp) classer. Le format est défini sur "#". |
| [PageNumberStamp](pagenumberstamp#constructor_1)(FormattedText) | Crée PageNumberStamp par texte formaté. |
| [PageNumberStamp](pagenumberstamp#constructor_2)(string) | Initialise une nouvelle instance du[`PageNumberStamp`](../pagenumberstamp) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Définit ou obtient une valeur booléenne qui indique que le contenu est tamponné en arrière-plan. Si la valeur est true, le contenu du tampon est posé en bas. Par défaut, la valeur est false, le contenu du tampon est posé en haut. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Obtient ou définit la marge inférieure du tampon. |
| [Draw](../../aspose.pdf/textstamp/draw) { get; set; } | Cette propriété détermine la manière dont le tampon est dessiné sur la page. Si Draw = true le tampon est dessiné sous forme d'opérateurs graphiques et si draw = false alors le tampon est dessiné sous forme de texte. |
| [Format](../../aspose.pdf/pagenumberstamp/format) { get; set; } | Valeur de chaîne pour tamponner les numéros de page. La valeur doit inclure le caractère '#' qui est remplacé par le numéro de page dans le processus d'estampage. |
| override [Height](../../aspose.pdf/textstamp/height) { get; set; } | Hauteur souhaitée du tampon sur la page. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Obtient ou définit l'alignement horizontal du tampon sur la page. |
| [Justify](../../aspose.pdf/textstamp/justify) { get; set; } | Définit la justification du texte. Si cette propriété est définie sur true, les bords gauche et droit du texte sont alignés. Valeur par défaut : faux. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Obtient ou définit la marge gauche du tampon. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth) { get; set; } | Hauteur de ligne maximale pour l'option WordWrap. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle) { get; set; } | Style de numérotation utilisé par ce tampon. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Obtient ou définit une valeur pour indiquer l'opacité du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Obtient ou définit une valeur pour indiquer l'opacité du contour du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Obtient ou définit une valeur de la largeur du contour du tampon. Par défaut, la valeur est 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Obtient ou définit la marge droite du tampon. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Définit ou obtient la rotation du contenu du tampon en fonction[`Rotation`](../rotation) valeurs. Remarque. Cette propriété concerne les angles définis qui sont des multiples de 90 degrés (0, 90, 180, 270 degrés). Pour définir un angle arbitraire, utilisez la propriété RotateAngle. Si l'angle défini par ArbitraryAngle n'est pas multiple de 90, la propriété Rotate renvoie Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Obtient ou définit l'angle de rotation du tampon en degrés. Cette propriété permet de définir un angle de rotation arbitraire. |
| [Scale](../../aspose.pdf/textstamp/scale) { get; set; } | Définit l'échelle du texte. Si cette propriété est définie sur true et que la valeur Width est spécifiée, le texte sera mis à l'échelle afin de s'adapter à la largeur spécifiée. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber) { get; set; } | Obtient ou définit la valeur du nombre de pages de démarrage. Les autres pages seront numérotées à partir de cette valeur. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment) { get; set; } | Alignement du texte à l'intérieur du tampon. |
| [TextState](../../aspose.pdf/textstamp/textstate) { get; } | Obtient les propriétés de texte du tampon. Voir[`TextState`](../textstamp/textstate) pour plus de détails. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Obtient ou définit la marge supérieure du tampon. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline) { get; set; } | Définit l'origine des coordonnées pour placer le texte. Si TreatYIndentAsBaseLine = true (par défaut lorsque Draw = true) La valeur YIndent sera traitée comme la ligne de base du texte. If TreatYIndentAsBaseLine = false (par défaut lorsque Draw = false) La valeur YIndent sera traitée comme bottom ( ligne de descente) du texte. |
| [Value](../../aspose.pdf/textstamp/value) { get; set; } | Obtient ou définit la valeur de chaîne qui est utilisée comme tampon sur la page. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Obtient ou définit l'alignement vertical du tampon sur la page. |
| override [Width](../../aspose.pdf/textstamp/width) { get; set; } | Largeur souhaitée du tampon sur la page. |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap) { get; set; } | Définit le retour à la ligne. Si cette propriété est définie sur true et que la valeur Width est spécifiée, le texte sera divisé sur plusieurs lignes pour s'adapter à la largeur spécifiée. Valeur par défaut : faux. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Coordonnée horizontale du tampon, en partant de la gauche. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Coordonnée verticale du tampon, en partant du bas. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Facteur de zoom du tampon. Permet de mettre à l'échelle le tampon. Veuillez noter que la paire de propriétés ZoomX et ZoomY permet de définir le facteur de zoom pour chaque axe séparément. La définition de cette propriété modifie les propriétés ZoomX et ZoomY. Si ZoomX et ZoomY sont différents, la propriété Zoom renvoie la valeur ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Facteur de zoom horizontal du tampon. Permet de redimensionner le tampon horizontalement. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Facteur de zoom vertical du tampon. Permet de redimensionner le tampon verticalement. |

## Méthodes

| Nom | La description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Renvoie l'ID du tampon. |
| override [Put](../../aspose.pdf/pagenumberstamp/put)(Page) | Ajoute un numéro de page. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Définit l'ID de tampon. |

### Voir également

* class [TextStamp](../textstamp)
* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
