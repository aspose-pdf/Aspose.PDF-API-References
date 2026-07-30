---
title: "Classe TextFragment"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.TextFragment. Représente un fragment de texte Pdf"
type: docs
weight: 11120
url: /fr/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Représente un fragment de texte Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Initialise une nouvelle instance de l'objet `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | Crée l'objet `TextFragment` avec un seul objet [`TextSegment`](../textsegment/) à l'intérieur. Spécifie la chaîne de texte à l'intérieur du segment. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Initialise une nouvelle instance de l'objet `TextFragment` avec des positions [`TabStops`](../tabstops/) prédéfinies. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Crée l'objet `TextFragment` avec un seul objet [`TextSegment`](../textsegment/) à l'intérieur et des positions [`TabStops`](../tabstops/) prédéfinies. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Obtient la position du texte, représentée par l'objet `TextFragment`. Le YIndent de la structure Position représente la coordonnée de la ligne de base du fragment de texte. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Obtient ou définit la note de fin de paragraphe (pour la génération de PDF uniquement). |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Obtient ou définit la note de bas de page du paragraphe (pour la génération de PDF uniquement). |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Obtient l'objet formulaire qui contient le TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du fragment de texte. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Définit le lien hypertexte du fragment. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Obtient la page qui contient le TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Obtient ou définit la position du texte, représentée par l'objet `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Obtient le rectangle du TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Obtient les options de remplacement de texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Obtient les segments de texte du `TextFragment` actuel. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Obtient ou définit l'objet texte de type String que représente l'objet `TextFragment`. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Obtient ou définit les options d'édition de texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Obtient ou définit l'état du texte pour le texte que représente l'objet `TextFragment`. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du fragment de texte. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Obtient ou définit le nombre de lignes d'enroulement pour ce paragraphe (pour la génération de PDF uniquement). |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique le Z-order du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Clone le fragment. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Clone le fragment avec tous les segments. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Obtient le(s) [`TextSegment`](../textsegment/) représentant la partie spécifiée du texte du `TextFragment`. |

## Remarques

En quelques mots, l'objet `TextFragment` contient une liste d'objets [`TextSegment`](../textsegment/). En détail : le texte d'un document PDF dans Pdf est représenté par deux objets de base : `TextFragment` et [`TextSegment`](../textsegment/). Les différences entre eux sont principalement dépendantes du contexte. Considérons le scénario suivant. L'utilisateur recherche le texte "hello world" pour le manipuler, modifier ses propriétés, le visualiser, etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

La représentation physique du texte PDF est très complexe. Le texte "hello world" peut être composé de plusieurs segments de texte physiquement indépendants. Le modèle de texte Aspose.Pdf établit essentiellement que l'objet `TextFragment` fournit un ensemble d'opérations logiques uniques sur l'ensemble d'objets physiques [`TextSegment`](../textsegment/) qui représentent la requête de l'utilisateur. Dans le scénario de recherche de texte, `TextFragment` est la représentation logique du texte "hello world", et la collection d'objets [`TextSegment`](../textsegment/) représente tous les segments physiques qui composent l'objet texte "hello world". Ainsi, `TextFragment` se rapproche de la représentation logique du texte. Et [`TextSegment`](../textsegment/) se rapproche de la représentation physique du texte. Évidemment, chaque objet [`TextSegment`](../textsegment/) peut avoir sa propre police, couleur, propriétés de positionnement. `TextFragment` offre un moyen simple de modifier le texte avec ses propriétés : définir la police, la taille de police, la couleur de police, etc. Pendant ce temps, les objets [`TextSegment`](../textsegment/) sont accessibles et les utilisateurs peuvent manipuler les objets [`TextSegment`](../textsegment/) de manière indépendante. Notez que la modification des propriétés de TextFragment peut modifier la collection interne [`Segments`](./segments/) car TextFragment est un objet agrégé et il peut réarranger les segments internes ou les fusionner en un seul segment. Si votre exigence est de laisser la collection [`Segments`](./segments/) inchangée, veuillez modifier les segments internes individuellement.

## Exemples

L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte ainsi que sa police.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouver la police qui sera utilisée pour modifier la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier le texte et la police de la première occurrence de texte
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


