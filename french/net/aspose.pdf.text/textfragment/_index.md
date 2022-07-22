---
title: TextFragment
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente un fragment de texte Pdf.
type: docs
weight: 7100
url: /fr/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Représente un fragment de texte Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TextFragment](textfragment#constructor)() | Initialise la nouvelle instance du[`TextFragment`](../textfragment) objet. |
| [TextFragment](textfragment#constructor_2)(string) | Crée[`TextFragment`](../textfragment) objet avec un seul[`TextSegment`](../textsegment) objet à l'intérieur. Spécifie la chaîne de texte à l'intérieur du segment. |
| [TextFragment](textfragment#constructor_1)(TabStops) | Initialise la nouvelle instance du[`TextFragment`](../textfragment) objet avec prédéfini[`TabStops`](../tabstops) positions. |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | Crée[`TextFragment`](../textfragment) objet avec un seul[`TextSegment`](../textsegment) objet à l'intérieur et prédéfini[`TabStops`](../tabstops) positions. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Obtient la position du texte pour le texte, représenté par[`TextFragment`](../textfragment) object. L'YIndent de la structure Position représente la coordonnée de base du fragment de texte. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Obtient ou définit la note de fin de paragraphe. (pour la génération de pdf uniquement) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Obtient ou définit la note de bas de paragraphe. (pour la génération de pdf uniquement) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Obtient l'objet de formulaire qui contient le TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Obtient ou définit un alignement horizontal du fragment de texte. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Définit le lien hypertexte fragment |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtient ou définit qu'un paragraphe est en ligne. La valeur par défaut est false.(pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtient ou définit une valeur booléenne qui force la génération de ce paragraphe sur une nouvelle page. La valeur par défaut est false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste dans la même page avec le paragraphe suivant. La valeur par défaut est false.(for pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Obtient la page qui contient le TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Obtient ou définit la position du texte pour le texte, représenté par[`TextFragment`](../textfragment) objet. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Récupère le rectangle du TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Obtient les options de remplacement de texte. Les options définissent le comportement lorsque le texte fragmenté est remplacé par un texte plus court/long. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Obtient les segments de texte pour le courant[`TextFragment`](../textfragment) . |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Obtient ou définitString objet texte que le[`TextFragment`](../textfragment) l'objet représente. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Obtient ou définit l'état du texte pour le texte qui[`TextFragment`](../textfragment) l'objet représente. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Obtient ou définit un alignement vertical du fragment de texte. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Obtient ou définit le nombre de lignes d'habillage pour ce paragraphe (pour la génération de pdf uniquement) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé sur le graphique avec un ZIndex plus petit. ZIndex peut être négatif. Le graphique avec ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | Clonez le fragment. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | Cloner le fragment avec tous les segments. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Obtient[`TextSegment`](../textsegment) (s) représentant une partie spécifiée du[`TextFragment`](../textfragment) texte. |

### Remarques

En quelques mots,[`TextFragment`](../textfragment) l'objet contient une liste de[`TextSegment`](../textsegment) objects. En détails : Texte du document pdf dansPdf est représenté par deux objets de base :[`TextFragment`](../textfragment) et[`TextSegment`](../textsegment) Les différences entre eux dépendent principalement du contexte. Considérons le scénario suivant. L'utilisateur recherche le texte "hello world" pour l'utiliser, modifier ses propriétés, etc. Physiquement, la représentation du texte pdf est très complexe. Le texte "hello world" peut être composé de plusieurs segments de texte physiquement indépendants. Le modèle de texte Aspose.Pdf établit essentiellement que[`TextFragment`](../textfragment) object fournit une opération logique unique définie sur physique[`TextSegment`](../textsegment) ensemble d'objets qui représentent la requête de l'utilisateur. Dans le scénario de recherche de texte,[`TextFragment`](../textfragment) est une représentation textuelle logique "hello world", et[`TextSegment`](../textsegment)la collection d'objets représente tous les segments physiques qui construisent l'objet texte "hello world". Donc,[`TextFragment`](../textfragment) est proche de la représentation logique du texte. Et[`TextSegment`](../textsegment) est proche de la représentation textuelle physique. Évidemment, chaque[`TextSegment`](../textsegment) l'objet peut avoir ses propres propriétés de police, de coloration et de positionnement. [`TextFragment`](../textfragment) fournit un moyen simple de modifier le texte avec ses propriétés : définir la police, définir la taille de la police, définir la couleur de la police, etc. [`TextSegment`](../textsegment) les objets sont accessibles et les utilisateurs peuvent opérer avec[`TextSegment`](../textsegment) objets indépendamment. Notez que la modification des propriétés TextFragment peut modifier[`Segments`](./segments) car TextFragment est un objet agrégé et il peut réorganiser les segments internes ou les fusionner en un seul segment. Si votre exigence est de quitter le[`Segments`](./segments)collection inchangée, veuillez modifier les segments internes individuellement.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Exemples

L'exemple montre comment rechercher du texte sur la première page du document PDF et remplacer le texte et sa police.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouve la police qui sera utilisée pour changer la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crée un objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Changer le texte et la police de la première occurrence de texte
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir également

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
