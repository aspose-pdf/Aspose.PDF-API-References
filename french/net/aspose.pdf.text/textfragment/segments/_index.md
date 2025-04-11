---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextFragment. Obtient les segments de texte pour le TextFragment actuel
type: docs
weight: 120
url: /fr/net/aspose.pdf.text/textfragment/segments/
---
## Propriété TextFragment.Segments

Obtient les segments de texte pour le [`TextFragment`](../) actuel.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Remarques

En quelques mots, les objets [`TextSegment`](../../textsegment/) sont des enfants de l'objet [`TextFragment`](../). Les utilisateurs avancés peuvent accéder directement aux segments pour effectuer des scénarios d'édition de texte plus complexes. Pour plus de détails, veuillez consulter la description de l'objet [`TextFragment`](../).

## Exemples

L'exemple démontre comment naviguer à travers tous les objets [`TextSegment`](../../textsegment/) à l'intérieur du [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Navigate all text segments and out their text and placement info
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### Voir aussi

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextSegment](../../textsegment/)
* classe [TextSegmentCollection](../../textsegmentcollection/)
* classe [TextFragment](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)