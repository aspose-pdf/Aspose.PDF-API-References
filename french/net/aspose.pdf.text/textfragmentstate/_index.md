---
title: "Classe TextFragmentState"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Text.TextFragmentState class. Représente l'état du texte d'un fragment de texte"
type: docs
weight: 11150
url: /fr/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Représente l'état du texte d'un fragment de texte.

```csharp
public sealed class TextFragmentState : TextState
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Initialise une nouvelle instance de l'objet `TextFragmentState` avec l'objet [`TextFragment`](../textfragment/) spécifié. Cette initialisation de `TextFragmentState` n'est pas prise en charge. TextFragmentState n'est disponible qu'avec la propriété [`TextState`](../textfragment/textstate/). |

## Propriétés

| Nom | Description |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Définit la couleur d'arrière-plan du texte, représentée par l'objet [`TextFragment`](../textfragment/) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Obtient ou définit l'espacement des caractères du texte, représenté par l'objet [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Obtient ou définit le CoordinateOrigin du texte. Si le CoordinateOrigin est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si le CoordinateOrigin est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur Descent de la police est trop grande, le texte peut être rendu plus haut que d'autres polices. Dans ce cas, le CoordinateOrigin BaseLine peut être sélectionné pour un meilleur rendu du texte. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Obtient ou définit le drapeau indiquant si la bordure du rectangle de texte est dessinée. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Obtient ou définit la police du texte, représentée par l'objet [`TextFragment`](../textfragment/) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Obtient ou définit la taille de police du texte, représentée par l'objet [`TextFragment`](../textfragment/) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Définit le style de police du texte, représenté par l'objet [`TextFragment`](../textfragment/) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Obtient ou définit la couleur de premier plan du texte, représentée par l'objet [`TextFragment`](../textfragment/) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Obtient ou définit les options de formatage. La définition des options ne sera effective que dans les scénarios de génération. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Obtient ou définit l'alignement horizontal du texte. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Obtient ou définit l'échelle horizontale du texte, représentée par l'objet [`TextFragment`](../textfragment/) |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Obtient ou définit l'invisibilité du texte. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Obtient ou définit l'espacement des lignes du texte. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Obtient ou définit le mode de rendu du texte. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Obtient ou définit l'angle de rotation en degrés. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Obtient ou définit le texte barré, représenté par l'objet [`TextFragment`](../textfragment/) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Obtient ou définit les opérations de tracé de couleur du rendu de [`TextFragment`](../textfragment/) (texte tracé, bordure du rectangle) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Obtient ou définit le texte en indice, représenté par l'objet [`TextFragment`](../textfragment/) |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Obtient ou définit le texte en exposant, représenté par l'objet [`TextFragment`](../textfragment/) |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Obtient les tabulations du texte. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | Vous pouvez placer cette balise dans le texte pour déclarer une tabulation. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Obtient ou définit le texte souligné, représenté par l'objet [`TextFragment`](../textfragment/). |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Obtient ou définit l'espacement des mots du texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Applique les paramètres d'un autre textState. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Vérifie si la chaîne d'entrée peut être placée à l'intérieur du rectangle défini. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Mesure la hauteur des caractères. (2 méthodes) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Mesure la chaîne. |

## Champs

| Nom | Description |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Valeur par défaut de la tabulation dans les largeurs du caractère espace de la police par défaut. |

## Remarques

Fournit un moyen de modifier les propriétés suivantes du texte : police ([`Font`](./font/) propriété) taille de police ([`FontSize`](./fontsize/) propriété) style de police ([`FontStyle`](./fontstyle/) propriété) couleur de premier plan ([`ForegroundColor`](./foregroundcolor/) propriété) couleur d'arrière-plan ([`BackgroundColor`](./backgroundcolor/) propriété) Notez que la modification des propriétés de `TextFragmentState` peut modifier la collection interne [`Segments`](../textfragment/segments/) car TextFragment est un objet agrégé et il peut réarranger les segments internes ou les fusionner en un seul segment. Si votre exigence est de laisser la collection [`Segments`](../textfragment/segments/) inchangée, veuillez modifier les segments internes individuellement.

## Exemples

L'exemple montre comment modifier la couleur du texte et la taille de police du texte avec l'objet [`TextState`](../textstate/).

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier la couleur de premier plan de la première occurrence du texte
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Modifier la taille de police de la première occurrence du texte
absorber.TextFragments[1].TextState.FontSize = 15;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


