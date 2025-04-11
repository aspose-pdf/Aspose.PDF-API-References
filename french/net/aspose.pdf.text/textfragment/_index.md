---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextFragment. Représente un fragment de texte Pdf
type: docs
weight: 10940
url: /fr/net/aspose.pdf.text/textfragment/
---
## Classe TextFragment

Représente un fragment de texte Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Initialise une nouvelle instance de l'objet `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | Crée un objet `TextFragment` avec un seul objet [`TextSegment`](../textsegment/) à l'intérieur. Spécifie la chaîne de texte à l'intérieur du segment. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Initialise une nouvelle instance de l'objet `TextFragment` avec des positions [`TabStops`](../tabstops/) prédéfinies. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Crée un objet `TextFragment` avec un seul objet [`TextSegment`](../textsegment/) à l'intérieur et des positions [`TabStops`](../tabstops/) prédéfinies. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Obtient la position du texte pour le texte, représenté par l'objet `TextFragment`. Le YIndent de la structure Position représente la coordonnée de base du fragment de texte. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Obtient ou définit la note de fin de paragraphe. (pour la génération de pdf uniquement) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Obtient ou définit la note de bas de page du paragraphe. (pour la génération de pdf uniquement) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Obtient l'objet de formulaire qui contient le TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du fragment de texte. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Définit l'hyperlien du fragment |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page que le paragraphe suivant. Par défaut, c'est faux. (pour la génération de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Obtient la page qui contient le TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Obtient ou définit la position du texte pour le texte, représenté par l'objet `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Obtient le rectangle du TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Obtient les options de remplacement de texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court/plus long. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Obtient les segments de texte pour le `TextFragment` actuel. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Obtient ou définit l'objet de texte String que l'objet `TextFragment` représente. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Obtient ou définit les options d'édition de texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Obtient ou définit l'état du texte pour le texte que l'objet `TextFragment` représente. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du fragment de texte. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Obtient ou définit le nombre de lignes à envelopper pour ce paragraphe (pour la génération de pdf uniquement) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Clone le fragment. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Clone le fragment avec tous les segments. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Obtient les [`TextSegment`](../textsegment/)(s) représentant la partie spécifiée du texte `TextFragment`. |

## Remarques

En quelques mots, l'objet `TextFragment` contient une liste d'objets [`TextSegment`](../textsegment/). En détail : Le texte d'un document pdf est représenté par deux objets de base : `TextFragment` et [`TextSegment`](../textsegment/). Les différences entre eux dépendent principalement du contexte. Considérons le scénario suivant. L'utilisateur recherche le texte "hello world" pour interagir avec, modifier ses propriétés, le visualiser, etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

La représentation physique du texte pdf est très complexe. Le texte "hello world" peut consister en plusieurs segments de texte physiquement indépendants. Le modèle de texte Aspose.Pdf établit essentiellement que l'objet `TextFragment` fournit un ensemble d'opérations logiques unique sur l'ensemble des objets physiques [`TextSegment`](../textsegment/) qui représentent la requête de l'utilisateur. Dans le scénario de recherche de texte, `TextFragment` est la représentation logique du texte "hello world", et la collection d'objets [`TextSegment`](../textsegment/) représente tous les segments physiques qui construisent l'objet texte "hello world". Ainsi, `TextFragment` est proche de la représentation textuelle logique. Et [`TextSegment`](../textsegment/) est proche de la représentation textuelle physique. Évidemment, chaque objet [`TextSegment`](../textsegment/) peut avoir sa propre police, ses propriétés de couleur et de positionnement. `TextFragment` fournit un moyen simple de modifier le texte avec ses propriétés : définir la police, définir la taille de la police, définir la couleur de la police, etc. Pendant ce temps, les objets [`TextSegment`](../textsegment/) sont accessibles et les utilisateurs peuvent interagir avec les objets [`TextSegment`](../textsegment/) de manière indépendante. Notez que modifier les propriétés de TextFragment peut changer la collection interne [`Segments`](./segments/) car TextFragment est un objet agrégat et il peut réorganiser les segments internes ou les fusionner en un seul segment. Si votre exigence est de laisser la collection [`Segments`](./segments/) inchangée, veuillez modifier les segments internes individuellement.

## Exemples

L'exemple démontre comment trouver du texte sur la première page du document PDF et remplacer le texte et sa police.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* classe [BaseParagraph](../../aspose.pdf/baseparagraph/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)