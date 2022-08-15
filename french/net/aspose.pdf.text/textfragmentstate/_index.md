---
title: TextFragmentState
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente un état de texte dun fragment de texte.
type: docs
weight: 7130
url: /fr/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Représente un état de texte d'un fragment de texte.

```csharp
public sealed class TextFragmentState : TextState
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TextFragmentState](textfragmentstate)(TextFragment) | Initialise la nouvelle instance du[`TextFragmentState`](../textfragmentstate) objet avec spécifié[`TextFragment`](../textfragment) objet. Ce[`TextFragmentState`](../textfragmentstate) l'initialisation n'est pas prise en charge. TextFragmentState n'est disponible qu'avec[`TextState`](../textfragment/textstate) propriété. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor) { get; set; } | Définit la couleur d'arrière-plan du texte, représentée par le[`TextFragment`](../textfragment) objet |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing) { get; set; } | Obtient ou définit l'espacement des caractères du texte, représenté par le[`TextFragment`](../textfragment) objet. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder) { get; set; } | Obtient ou définit si la bordure du rectangle de texte est dessinée. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font) { get; set; } | Obtient ou définit la police du texte, représentée par le[`TextFragment`](../textfragment) objet |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize) { get; set; } | Obtient ou définit la taille de la police du texte, représentée par le[`TextFragment`](../textfragment) objet |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle) { get; set; } | Définit le style de police du texte, représenté par le[`TextFragment`](../textfragment) objet |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor) { get; set; } | Obtient ou définit la couleur de premier plan du texte, représentée par le[`TextFragment`](../textfragment) objet |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions) { get; set; } | Obtient ou définit les options de formatage. La définition des options ne sera effective que dans les scénarios de générateur. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment) { get; set; } | Obtient ou définit l'alignement horizontal du texte. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling) { get; set; } | Obtient ou définit l'échelle horizontale du texte, représentée par le[`TextFragment`](../textfragment) objet. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible) { get; set; } | Obtient ou définit l'invisibilité du texte. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing) { get; set; } | Obtient ou définit l'interligne du texte. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode) { get; set; } | Obtient ou définit le mode de rendu du texte. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation) { get; set; } | Obtient ou définit l'angle de rotation en degrés. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout) { set; } | Définit le texte barré, représenté par le[`TextFragment`](../textfragment) objet |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor) { get; set; } | Obtient ou définit les opérations de contour de couleur de[`TextFragment`](../textfragment) rendu (texte en trait, bordure rectangulaire) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript) { get; set; } | Obtient ou définit l'indice du texte, représenté par le[`TextFragment`](../textfragment) objet. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript) { get; set; } | Obtient ou définit l'exposant du texte, représenté par le[`TextFragment`](../textfragment) objet. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops) { get; } | Obtient des tabulations pour le texte. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline) { get; set; } | Obtient ou définit le soulignement du texte, représenté par le[`TextFragment`](../textfragment) objet |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing) { get; set; } | Obtient ou définit l'espacement des mots du texte. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom)(TextState) | Applique les paramètres d'un autre textState. |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring)(string) | Mesure la chaîne. |

## Des champs

| Nom | La description |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | Valeur par défaut de la tabulation en largeurs de caractère d'espacement de la police par défaut. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | Vous pouvez placer cette balise dans le texte pour déclarer la tabulation. |

### Remarques

Fournit un moyen de modifier les propriétés suivantes du texte : font ([`Font`](./font) propriété) taille de la police ([`FontSize`](./fontsize) propriété) style de police ([`FontStyle`](./fontstyle) propriété) couleur de premier plan ([`ForegroundColor`](./foregroundcolor) propriété) couleur d'arrière-plan ([`BackgroundColor`](./backgroundcolor) propriété) Notez que la modification[`TextFragmentState`](../textfragmentstate) les propriétés peuvent changer à l'intérieur[`Segments`](../textfragment/segments) car TextFragment est un objet agrégé et il peut réorganiser les segments internes ou les fusionner en un seul segment. Si votre exigence est de quitter le[`Segments`](../textfragment/segments) collection inchangée, veuillez modifier les segments internes individuellement.

### Exemples

L'exemple montre comment changer la couleur du texte et la taille de la police du texte avec[`TextState`](../textstate) objet.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Crée un objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Changer la couleur de premier plan de la première occurrence de texte
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Changer la taille de la police de la première occurrence de texte
absorber.TextFragments[1].TextState.FontSize = 15;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir également

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* class [TextState](../textstate)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
