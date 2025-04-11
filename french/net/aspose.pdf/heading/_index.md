---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Heading. Représente un en-tête
type: docs
weight: 5470
url: /fr/net/aspose.pdf/heading/
---
## Classe Heading

Représente un en-tête.

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
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Obtient la position du texte pour le texte, représenté par un objet [`TextFragment`](../../aspose.pdf.text/textfragment/). Le YIndent de la structure Position représente la coordonnée de base du fragment de texte. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Obtient la page de destination. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Obtient ou définit la note de fin du paragraphe. (pour la génération de pdf uniquement) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Obtient ou définit la note de bas de page du paragraphe. (pour la génération de pdf uniquement) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Obtient l'objet de formulaire qui contient le TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du fragment de texte. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Définit le lien hypertexte du fragment |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Obtient que l'en-tête doit être numéroté automatiquement. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération de pdf) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Obtient que l'en-tête doit être dans la liste de la table des matières. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page que le paragraphe suivant. La valeur par défaut est false. (pour la génération de pdf) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Obtient le niveau. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Obtient la page qui contient le TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Obtient ou définit la position du texte pour le texte, représenté par un objet [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Obtient le rectangle du TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Obtient les options de remplacement de texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Obtient les segments de texte pour le [`TextFragment`](../../aspose.pdf.text/textfragment/) actuel. |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Obtient le numéro de départ de l'en-tête. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Obtient ou définit le style. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Obtient ou définit l'objet texte String que représente l'objet [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Obtient ou définit les options d'édition de texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Obtient ou définit l'état du texte pour le texte que représente l'objet [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Obtient la page qui contient cet en-tête. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Obtient le Y supérieur de ces en-têtes. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Obtient ou définit l'étiquette utilisateur. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du fragment de texte. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Obtient ou définit le nombre de lignes à envelopper pour ce paragraphe (pour la génération de pdf uniquement) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Clone l'en-tête. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Clone l'en-tête avec tous les segments. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Obtient les [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) représentant la partie spécifiée du texte [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### Voir aussi

* classe [TextFragment](../../aspose.pdf.text/textfragment/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)