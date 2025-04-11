---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextFragmentState. Représente un état de texte d'un fragment de texte
type: docs
weight: 10970
url: /fr/net/aspose.pdf.text/textfragmentstate/
---
## Classe TextFragmentState

Représente un état de texte d'un fragment de texte.

```csharp
public sealed class TextFragmentState : TextState
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Initialise une nouvelle instance de l'objet `TextFragmentState` avec l'objet [`TextFragment`](../textfragment/) spécifié. Cette initialisation de `TextFragmentState` n'est pas supportée. TextFragmentState est uniquement disponible avec la propriété [`TextState`](../textfragment/textstate/). |

## Propriétés

| Nom | Description |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Définit la couleur de fond du texte, représentée par l'objet [`TextFragment`](../textfragment/) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Obtient ou définit l'espacement des caractères du texte, représenté par l'objet [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Obtient ou définit l'origine des coordonnées du texte. Si l'origine des coordonnées est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si l'origine des coordonnées est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur de descente de la police est trop grande, le texte peut être rendu plus haut que d'autres polices. Dans ce cas, l'origine des coordonnées BaseLine peut être sélectionnée pour un meilleur rendu du texte. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Obtient ou définit si le drapeau de bordure du rectangle de texte est dessiné. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Obtient ou définit la police du texte, représentée par l'objet [`TextFragment`](../textfragment/) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Obtient ou définit la taille de la police du texte, représentée par l'objet [`TextFragment`](../textfragment/) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Définit le style de police du texte, représenté par l'objet [`TextFragment`](../textfragment/) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Obtient ou définit la couleur de premier plan du texte, représentée par l'objet [`TextFragment`](../textfragment/) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Obtient ou définit les options de formatage. Le réglage des options sera effectif uniquement dans les scénarios de générateur. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Obtient ou définit l'alignement horizontal pour le texte. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Obtient ou définit l'échelle horizontale du texte, représentée par l'objet [`TextFragment`](../textfragment/). |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Obtient ou définit l'invisibilité du texte. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Obtient ou définit l'espacement des lignes du texte. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Obtient ou définit le mode de rendu du texte. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Obtient ou définit l'angle de rotation en degrés. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Obtient ou définit le barré pour le texte, représenté par l'objet [`TextFragment`](../textfragment/) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Obtient ou définit la couleur des opérations de contour de rendu de [`TextFragment`](../textfragment/) (texte de contour, bordure de rectangle) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Obtient ou définit l'indice du texte, représenté par l'objet [`TextFragment`](../textfragment/) |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Obtient ou définit le surindice du texte, représenté par l'objet [`TextFragment`](../textfragment/) |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Obtient les tabulations pour le texte. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Obtient ou définit le soulignement pour le texte, représenté par l'objet [`TextFragment`](../textfragment/) |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Obtient ou définit l'espacement des mots du texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Applique les paramètres d'un autre textState. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Vérifie si la chaîne d'entrée peut être placée à l'intérieur du rectangle défini. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Mesure la hauteur du caractère. (2 méthodes) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Mesure la chaîne. |

## Champs

| Nom | Description |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Valeur par défaut de la tabulation dans les largeurs du caractère d'espace de la police par défaut. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Vous pouvez placer cette balise dans le texte pour déclarer une tabulation. |

## Remarques

Fournit un moyen de changer les propriétés suivantes du texte : police ([`Font`](./font/) propriété) taille de police ([`FontSize`](./fontsize/) propriété) style de police ([`FontStyle`](./fontstyle/) propriété) couleur de premier plan ([`ForegroundColor`](./foregroundcolor/) propriété) couleur de fond ([`BackgroundColor`](./backgroundcolor/) propriété) Notez que changer les propriétés de `TextFragmentState` peut modifier la collection interne [`Segments`](../textfragment/segments/) car TextFragment est un objet agrégat et il peut réorganiser les segments internes ou les fusionner en un seul segment. Si votre exigence est de laisser la collection [`Segments`](../textfragment/segments/) inchangée, veuillez modifier les segments internes individuellement.

## Exemples

L'exemple démontre comment changer la couleur du texte et la taille de la police du texte avec l'objet [`TextState`](../textstate/).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* classe [TextFragmentAbsorber](../textfragmentabsorber/)
* classe [Document](../../aspose.pdf/document/)
* classe [TextState](../textstate/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)