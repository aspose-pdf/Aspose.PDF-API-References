---
title: "Classe TextStamp"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.TextStamp. Représente un tampon textuel"
type: docs
weight: 11270
url: /fr/net/aspose.pdf/textstamp/
---
## TextStamp class

Représente un tampon textuel.

```csharp
public class TextStamp : Stamp
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextStamp](textstamp/#constructor)(FormattedText) | Initialise une nouvelle instance de la classe `TextStamp` avec l'objet formattedText |
| [TextStamp](textstamp/#constructor_1)(string) | Initialise une nouvelle instance de la classe `TextStamp`. |
| [TextStamp](textstamp/#constructor_2)(string, TextState) | Initialise une nouvelle instance de la classe `TextStamp`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Ajuste automatiquement la précision de la taille de police. Valeur par défaut : 0,1 ; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Si activé, la taille de police sera automatiquement ajustée pour s'adapter au rectangle du tampon de taille : [`Width`](./width/) et [`Height`](./height/). La largeur et la hauteur par défaut sont dérivées du rectangle de la page. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Définit ou récupère une valeur booléenne indiquant que le contenu est tamponné en arrière-plan. Si la valeur est vraie, le contenu du tampon est placé en bas. Par défaut, la valeur est fausse, le contenu du tampon est placé en haut. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Obtient ou définit la marge inférieure du tampon. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Cette propriété détermine comment le tampon est dessiné sur la page. Si Draw = true, le tampon est dessiné comme des opérateurs graphiques et si draw = false, le tampon est dessiné comme du texte. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Taille de police réelle après le placement du tampon. (Peut différer de la taille de police initiale fournie via le constructeur si l'option 'AutoAdjustFontSizeToFitStampRectangle' est activée.) |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Hauteur souhaitée du tampon sur la page. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Obtient ou définit l'alignement horizontal du tampon sur la page. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Définit la justification du texte. Si cette propriété est définie sur true, les bords gauche et droit du texte sont alignés. Valeur par défaut : false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Obtient ou définit la marge gauche du tampon. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Hauteur maximale de ligne pour l'option WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Obtient ou définit le mode qui définit le comportement dans le cas où les polices ne contiennent pas les caractères demandés. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Obtient ou définit une valeur indiquant l'opacité du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Obtient ou définit une valeur indiquant l'opacité du contour du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Obtient ou définit la valeur de la largeur du contour du tampon. Par défaut, la valeur est 1,0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Obtient ou définit la marge droite du tampon. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Définit ou récupère la rotation du contenu du tampon selon les valeurs [`Rotation`](../rotation/). Remarque : cette propriété sert à définir des angles qui sont des multiples de 90 degrés (0, 90, 180, 270 degrés). Pour définir un angle arbitraire, utilisez la propriété RotateAngle. Si l'angle défini par ArbitraryAngle n'est pas un multiple de 90, alors la propriété Rotate renvoie Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Obtient ou définit l'angle de rotation du tampon en degrés. Cette propriété permet de définir un angle de rotation arbitraire. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Définit le redimensionnement du texte. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera mis à l'échelle afin de s'adapter à la largeur spécifiée. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Alignement du texte à l'intérieur du tampon. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Obtient les propriétés texte du tampon. Voir [`TextState`](./textstate/) pour plus de détails. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Obtient ou définit la marge supérieure du tampon. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Définit l'origine des coordonnées pour placer le texte. Si TreatYIndentAsBaseLine = true (valeur par défaut lorsque Draw = true), la valeur YIndent sera considérée comme la ligne de base du texte. Si TreatYIndentAsBaseLine = false (valeur par défaut lorsque Draw = false), la valeur YIndent sera considérée comme le bas (ligne de descente) du texte. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Obtient ou définit la valeur de chaîne utilisée comme tampon sur la page. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Obtient ou définit l'alignement vertical du tampon sur la page. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Largeur souhaitée du tampon sur la page. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Obtient ou définit le mode de retour à la ligne pour le rendu du texte. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Coordonnée horizontale du tampon, à partir de la gauche. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Coordonnée verticale du tampon, à partir du bas. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Facteur de zoom du tampon. Permet de mettre à l'échelle le tampon. Veuillez noter que la paire de propriétés ZoomX et ZoomY permet de définir le facteur de zoom pour chaque axe séparément. La définition de cette propriété modifie les propriétés ZoomX et ZoomY. Si ZoomX et ZoomY sont différents, la propriété Zoom renvoie la valeur de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Facteur de zoom horizontal du tampon. Permet de mettre à l'échelle le tampon horizontalement. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Facteur de zoom vertical du tampon. Permet de mettre à l'échelle le tampon verticalement. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Renvoie l'ID du tampon. |
| override [Put](../../aspose.pdf/textstamp/put/)(Page) | Ajoute un tampon textuel sur la page. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Définit l'ID du tampon. |

## Autres membres

| Nom | Description |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | Action à exécuter si la police ne contient pas le caractère requis. |

### Voir aussi

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


