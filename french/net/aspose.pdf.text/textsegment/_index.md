---
title: "Classe TextSegment"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.TextSegment. Représente un segment de texte Pdf"
type: docs
weight: 11240
url: /fr/net/aspose.pdf.text/textsegment/
---
## TextSegment class

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
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Obtient la position du texte, représentée par l'objet `TextSegment`. L'YIndent de la structure Position représente la coordonnée de la ligne de base du segment de texte. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Obtient la collection d'objets CharInfo qui représentent les informations sur les caractères du segment de texte. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Obtient l'index du caractère de fin du segment actuel dans l'opérateur d'affichage du texte (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Obtient ou définit le lien hypertexte du segment (pour le générateur pdf). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Obtient la position du texte, représentée par l'objet `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Obtient le rectangle du TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Obtient l'index du caractère de début du segment actuel dans l'opérateur d'affichage du texte (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Obtient ou définit l'objet texte String que représente l'objet `TextSegment`. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Obtient ou définit les options d'édition de texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Obtient ou définit l'état du texte pour le texte que représente l'objet `TextSegment`. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Encode la chaîne en html. |

## Remarques

En quelques mots, les objets `TextSegment` sont des enfants de l'objet [`TextFragment`](../textfragment/). En détail : le texte d'un document pdf dans Pdf est représenté par deux objets de base : [`TextFragment`](../textfragment/) et `TextSegment`. Les différences entre eux sont principalement dépendantes du contexte. Considérons le scénario suivant. L'utilisateur recherche le texte "hello world" pour le manipuler, modifier ses propriétés, etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

La représentation physique du texte pdf est très complexe. Le texte "hello world" peut être composé de plusieurs segments de texte physiquement indépendants. Le modèle texte d'Aspose.Pdf établit essentiellement que l'objet [`TextFragment`](../textfragment/) fournit un ensemble d'opérations logiques unique sur l'ensemble d'objets `TextSegment` physiques qui représentent la requête de l'utilisateur. Dans un scénario de recherche de texte, [`TextFragment`](../textfragment/) est la représentation logique du texte "hello world", et la collection d'objets `TextSegment` représente tous les segments physiques qui construisent l'objet texte "hello world". Ainsi, [`TextFragment`](../textfragment/) se rapproche de la représentation logique du texte. Et `TextSegment` se rapproche de la représentation physique du texte. Évidemment, chaque objet `TextSegment` peut avoir sa propre police, couleur et propriétés de positionnement. [`TextFragment`](../textfragment/) offre un moyen simple de modifier le texte avec ses propriétés : définir la police, la taille de police, la couleur de police, etc. Pendant ce temps, les objets `TextSegment` sont accessibles et les utilisateurs peuvent manipuler les objets `TextSegment` de façon indépendante.

## Exemples

L'exemple montre comment changer la couleur du texte et la taille de la police du texte à l'aide de l'objet [`TextState`](./textstate/) du `TextSegment`.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier la couleur de premier plan du premier segment de texte de la première occurrence de texte
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Modifier la taille de police du premier segment de texte de la première occurrence de texte
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


