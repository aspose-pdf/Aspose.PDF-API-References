---
title: TextSegment
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente un segment de texte PDF.
type: docs
weight: 7210
url: /fr/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Représente un segment de texte PDF.

```csharp
public sealed class TextSegment
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TextSegment](textsegment#constructor)() | Crée un objet TextSegment. |
| [TextSegment](textsegment#constructor_1)(string) | Crée un objet TextSegment. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition) { get; set; } | Obtient la position du texte pour le texte, représenté par[`TextSegment`](../textsegment) object. L'YIndent de la structure Position représente la coordonnée de base du segment de texte. |
| [Characters](../../aspose.pdf.text/textsegment/characters) { get; } | Obtient une collection d'objets CharInfo qui représentent des informations sur les caractères dans le segment de texte. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex) { get; } | Obtient l'index du caractère de fin du segment actuel dans le segment de l'opérateur de texte d'affichage (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink) { get; set; } | Obtient ou définit le lien hypertexte du segment (pour le générateur de pdf). |
| [Position](../../aspose.pdf.text/textsegment/position) { get; set; } | Obtient la position du texte pour le texte, représenté par[`TextSegment`](../textsegment) objet. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle) { get; } | Récupère le rectangle du TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex) { get; } | Obtient l'index du caractère de départ du segment actuel dans le segment de l'opérateur de texte d'affichage (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text) { get; set; } | Obtient ou définitString objet texte que le[`TextSegment`](../textsegment) l'objet représente. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions) { get; set; } | Obtient ou définit les options d'édition de texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [TextState](../../aspose.pdf.text/textsegment/textstate) { get; set; } | Obtient ou définit l'état du texte pour le texte qui[`TextSegment`](../textsegment) l'objet représente. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode)(string) | Encode la chaîne en html. |

### Remarques

En quelques mots,[`TextSegment`](../textsegment) les objets sont les enfants de[`TextFragment`](../textfragment) objet. En détails : Texte du document pdf dansPdf est représenté par deux objets de base :[`TextFragment`](../textfragment) et[`TextSegment`](../textsegment) Les différences entre eux dépendent principalement du contexte. Considérons le scénario suivant. L'utilisateur recherche le texte "hello world" pour l'utiliser, modifier ses propriétés, etc. Physiquement, la représentation du texte pdf est très complexe. Le texte "hello world" peut être composé de plusieurs segments de texte physiquement indépendants. Le modèle de texte Aspose.Pdf établit essentiellement que[`TextFragment`](../textfragment) object fournit une opération logique unique définie sur physique[`TextSegment`](../textsegment) ensemble d'objets qui représentent la requête de l'utilisateur. Dans le scénario de recherche de texte,[`TextFragment`](../textfragment) est une représentation textuelle logique "hello world", et[`TextSegment`](../textsegment)la collection d'objets représente tous les segments physiques qui construisent l'objet texte "hello world". Donc,[`TextFragment`](../textfragment) est proche de la représentation logique du texte. Et[`TextSegment`](../textsegment) est proche de la représentation textuelle physique. Évidemment, chaque[`TextSegment`](../textsegment) l'objet peut avoir ses propres propriétés de police, de coloration et de positionnement. [`TextFragment`](../textfragment) fournit un moyen simple de modifier le texte avec ses propriétés : définir la police, définir la taille de la police, définir la couleur de la police, etc. [`TextSegment`](../textsegment) les objets sont accessibles et les utilisateurs peuvent opérer avec[`TextSegment`](../textsegment) objets indépendamment.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Exemples

L'exemple montre comment changer la couleur du texte et la taille de la police du texte avec[`TextState`](./textstate) objet de[`TextSegment`](../textsegment) objet.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Crée un objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Changer la couleur de premier plan du premier segment de texte de la première occurrence de texte
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Changer la taille de la police du premier segment de texte de la première occurrence de texte
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir également

* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
