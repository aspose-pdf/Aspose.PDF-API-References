---
title: "Classe TextState"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.TextState. Représente l'état d'un texte"
type: docs
weight: 11260
url: /fr/net/aspose.pdf.text/textstate/
---
## TextState class

Représente l'état d'un texte

```csharp
public class TextState
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextState](textstate/#constructor)() | Crée un objet d'état de texte. |
| [TextState](textstate/#constructor_2)(Color) | Crée un objet d'état de texte avec spécification de la couleur de premier plan. |
| [TextState](textstate/#constructor_1)(double) | Crée un objet d'état de texte avec spécification de la taille de police. |
| [TextState](textstate/#constructor_4)(string) | Crée un objet d'état de texte avec spécification de la famille de police. |
| [TextState](textstate/#constructor_3)(Color, double) | Crée un objet d'état de texte avec spécification de la couleur de premier plan et de la taille de police. |
| [TextState](textstate/#constructor_6)(string, double) | Crée un objet d'état de texte avec spécification de la famille de police et de la taille de police. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | Crée un objet d'état de texte avec spécification de la famille de police et du style de police. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | Définit la couleur d'arrière-plan du texte. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | Obtient ou définit l'espacement des caractères du texte. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | Obtient ou définit le CoordinateOrigin du texte. Si le CoordinateOrigin est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si le CoordinateOrigin est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur Descent de la police est trop grande, le texte peut être rendu plus haut que d'autres polices. Dans ce cas, le CoordinateOrigin BaseLine peut être sélectionné pour un meilleur rendu du texte. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | Obtient ou définit la police du texte. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | Obtient ou définit la taille de police du texte. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | Définit le style de police du texte. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | Obtient ou définit la couleur de premier plan du texte. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | Obtient ou définit l'alignement horizontal du texte. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | Obtient ou définit l'échelle horizontale du texte. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | Obtient ou définit l'invisibilité du texte. Cela reflète essentiellement l'état de [`RenderingMode`](./renderingmode/), sauf dans certains cas particuliers (comme le rognage). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | Obtient ou définit l'espacement des lignes du texte. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | Obtient ou définit le mode de rendu du texte. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | Obtient ou définit le texte barré, représenté par l'objet [`TextSegment`](../textsegment/). |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | Obtient ou définit la couleur de premier plan du texte. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | Obtient ou définit le texte en indice. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | Obtient ou définit le texte en exposant. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | Vous pouvez placer cette balise dans le texte pour déclarer une tabulation. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | Obtient ou définit le texte souligné, représenté par l'objet [`TextFragment`](../textfragment/). |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | Obtient ou définit l'espacement des mots du texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | Applique les paramètres d'un autre textState. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | Mesure la hauteur du caractère. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | Mesure la chaîne. |

## Champs

| Nom | Description |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Valeur par défaut de la tabulation dans les largeurs du caractère espace de la police par défaut. |

### Voir aussi

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


