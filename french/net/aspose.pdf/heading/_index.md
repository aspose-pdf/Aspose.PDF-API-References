---
title: "Classe Heading"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Heading. Représente un titre"
type: docs
weight: 5590
url: /fr/net/aspose.pdf/heading/
---
## Heading class

Représente le titre.

```csharp
public sealed class Heading : TextFragment
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Heading](heading/)(int) | Initialise une nouvelle instance de la classe Cell. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Obtient la position du texte, représentée par l’objet [`TextFragment`](../../aspose.pdf.text/textfragment/). L’YIndent de la structure Position représente la coordonnée de la ligne de base du fragment de texte. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Obtient la page de destination. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Obtient ou définit la note de fin de paragraphe (pour la génération de PDF uniquement). |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Obtient ou définit la note de bas de page du paragraphe (pour la génération de PDF uniquement). |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Obtient l'objet formulaire qui contient le TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du fragment de texte. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Définit le lien hypertexte du fragment. |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Obtient si le titre doit être numéroté automatiquement. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération PDF) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Obtient si le titre doit apparaître dans la liste de la table des matières. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération PDF) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Obtient le niveau. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Obtient la page qui contient le TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Obtient ou définit la position du texte, représentée par l’objet [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Obtient le rectangle du TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Obtient les options de remplacement de texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Obtient les segments de texte pour le [`TextFragment`](../../aspose.pdf.text/textfragment/) actuel. |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Obtient le numéro de départ du titre. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Obtient ou définit le style. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Obtient ou définit l’objet texte de type String que représente l’objet [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Obtient ou définit les options d'édition de texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Obtient ou définit l’état du texte pour le texte que représente l’objet [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Obtient la page qui contient ce titre. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Obtient la coordonnée Y supérieure de ces titres. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Obtient ou définit l’étiquette utilisateur. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du fragment de texte. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Obtient ou définit le nombre de lignes d'enroulement pour ce paragraphe (pour la génération de PDF uniquement). |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique le Z-order du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Clone le titre. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Clone le titre avec tous les segments. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Obtient le(s) [`TextSegment`](../../aspose.pdf.text/textsegment/) représentant la partie spécifiée du texte du [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### Voir aussi

* class [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


