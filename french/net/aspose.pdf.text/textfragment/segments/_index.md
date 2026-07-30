---
title: "TextFragment.Segments"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextFragment. Obtient les segments de texte du TextFragment actuel."
type: docs
weight: 120
url: /fr/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments property

Obtient les segments de texte du [`TextFragment`](../) actuel.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Remarques

En quelques mots, les objets [`TextSegment`](../../textsegment/) sont des enfants de l'objet [`TextFragment`](../). Les utilisateurs avancés peuvent accéder directement aux segments pour réaliser des scénarios d'édition de texte plus complexes. Pour plus de détails, veuillez consulter la description de l'objet [`TextFragment`](../).

## Exemples

L'exemple montre comment parcourir tous les objets [`TextSegment`](../../textsegment/) à l'intérieur du [`TextFragment`](../).

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Parcourez tous les segments de texte et affichez leur texte ainsi que leurs informations de position.
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### Voir aussi

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


