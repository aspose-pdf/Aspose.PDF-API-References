---
title: Heading
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente le titre.
type: docs
weight: 3360
url: /fr/net/aspose.pdf/heading/
---
## Heading class

Représente le titre.

```csharp
public sealed class Heading : TextFragment
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Heading](heading)(int) | Initialise une nouvelle instance de la classe Cell. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Obtient la position du texte pour le texte, représenté par[`TextFragment`](../../aspose.pdf.text/textfragment) object. L'YIndent de la structure Position représente la coordonnée de base du fragment de texte. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage) { get; set; } | Obtient la page de destination. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Obtient ou définit la note de fin de paragraphe. (pour la génération de pdf uniquement) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Obtient ou définit la note de bas de paragraphe. (pour la génération de pdf uniquement) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Obtient l'objet de formulaire qui contient le TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Obtient ou définit un alignement horizontal du fragment de texte. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Définit le lien hypertexte fragment |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence) { get; set; } | Obtient que le titre doit être numéroté automatiquement. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtient ou définit qu'un paragraphe est en ligne. La valeur par défaut est false.(pour la génération de pdf) |
| [IsInList](../../aspose.pdf/heading/isinlist) { get; set; } | Obtient que le titre doit être dans la liste toc. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtient ou définit une valeur booléenne qui force la génération de ce paragraphe sur une nouvelle page. La valeur par défaut est false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste dans la même page avec le paragraphe suivant. La valeur par défaut est false.(for pdf generation) |
| [Level](../../aspose.pdf/heading/level) { get; set; } | Obtient le niveau. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Obtient la page qui contient le TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Obtient ou définit la position du texte pour le texte, représenté par[`TextFragment`](../../aspose.pdf.text/textfragment) objet. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Récupère le rectangle du TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Obtient les options de remplacement de texte. Les options définissent le comportement lorsque le texte fragmenté est remplacé par un texte plus court/long. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Obtient les segments de texte pour le courant[`TextFragment`](../../aspose.pdf.text/textfragment) . |
| [StartNumber](../../aspose.pdf/heading/startnumber) { get; set; } | Obtient le numéro de début du titre. |
| [Style](../../aspose.pdf/heading/style) { get; set; } | Obtient ou définit le style. |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Obtient ou définitString objet texte que le[`TextFragment`](../../aspose.pdf.text/textfragment) l'objet représente. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Obtient ou définit l'état du texte pour le texte qui[`TextFragment`](../../aspose.pdf.text/textfragment) l'objet représente. |
| [TocPage](../../aspose.pdf/heading/tocpage) { get; set; } | Obtient la page qui contient ce titre. |
| [Top](../../aspose.pdf/heading/top) { get; set; } | Obtient le premier Y de ces en-têtes. |
| [UserLabel](../../aspose.pdf/heading/userlabel) { get; set; } | Obtient ou définit le libellé de l'utilisateur. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Obtient ou définit un alignement vertical du fragment de texte. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Obtient ou définit le nombre de lignes d'habillage pour ce paragraphe (pour la génération de pdf uniquement) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé sur le graphique avec un ZIndex plus petit. ZIndex peut être négatif. Le graphique avec ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone)() | Cloner le titre. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments)() | Cloner le titre avec tous les segments. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Obtient[`TextSegment`](../../aspose.pdf.text/textsegment) (s) représentant une partie spécifiée du[`TextFragment`](../../aspose.pdf.text/textfragment) texte. |

### Voir également

* class [TextFragment](../../aspose.pdf.text/textfragment)
* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
