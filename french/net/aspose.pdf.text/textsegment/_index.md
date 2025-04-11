---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextSegment. Représente un segment de texte Pdf
type: docs
weight: 11050
url: /fr/net/aspose.pdf.text/textsegment/
---
## Classe TextSegment

Représente un segment de texte Pdf.

```csharp
public sealed class TextSegment
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | Crée un objet TextSegment. |
| [TextSegment](textsegment/#constructor_1)(string) | Crée un objet TextSegment. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Obtient la position du texte pour le texte, représenté par l'objet `TextSegment`. Le YIndent de la structure Position représente la coordonnée de base du segment de texte. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Obtient la collection d'objets CharInfo qui représentent des informations sur les caractères dans le segment de texte. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Obtient l'index du caractère de fin du segment actuel dans le segment de l'opérateur de texte affiché (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Obtient ou définit l'hyperlien du segment (pour le générateur pdf). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Obtient la position du texte pour le texte, représenté par l'objet `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Obtient le rectangle du TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Obtient l'index du caractère de début du segment actuel dans le segment de l'opérateur de texte affiché (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Obtient ou définit l'objet texte String que l'objet `TextSegment` représente. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Obtient ou définit les options d'édition de texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Obtient ou définit l'état du texte pour le texte que l'objet `TextSegment` représente. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Encode une chaîne en html. |

## Remarques

En quelques mots, les objets `TextSegment` sont des enfants de l'objet [`TextFragment`](../textfragment/). En détail : Le texte du document pdf dans Pdf est représenté par deux objets de base : [`TextFragment`](../textfragment/) et `TextSegment`. Les différences entre eux dépendent principalement du contexte. Considérons le scénario suivant. L'utilisateur recherche le texte "hello world" pour y opérer, changer ses propriétés, le visualiser, etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

La représentation physique du texte pdf est très complexe. Le texte "hello world" peut consister en plusieurs segments de texte physiquement indépendants. Le modèle de texte Aspose.Pdf établit essentiellement que l'objet [`TextFragment`](../textfragment/) fournit un ensemble d'opérations logiques unique sur l'ensemble des objets `TextSegment` physiques qui représentent la requête de l'utilisateur. Dans le scénario de recherche de texte, [`TextFragment`](../textfragment/) est la représentation logique du texte "hello world", et la collection d'objets `TextSegment` représente tous les segments physiques qui construisent l'objet texte "hello world". Ainsi, [`TextFragment`](../textfragment/) est proche de la représentation textuelle logique. Et `TextSegment` est proche de la représentation textuelle physique. Évidemment, chaque objet `TextSegment` peut avoir sa propre police, ses propriétés de couleur et de positionnement. [`TextFragment`](../textfragment/) fournit un moyen simple de changer le texte avec ses propriétés : définir la police, définir la taille de la police, définir la couleur de la police, etc. Pendant ce temps, les objets `TextSegment` sont accessibles et les utilisateurs peuvent opérer avec les objets `TextSegment` de manière indépendante.

## Exemples

L'exemple démontre comment changer la couleur du texte et la taille de la police du texte avec l'objet [`TextState`](./textstate/) de l'objet `TextSegment`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)