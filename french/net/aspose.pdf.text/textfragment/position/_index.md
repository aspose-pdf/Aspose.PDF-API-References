---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextFragment. Obtient ou définit la position du texte pour le texte représenté par l'objet TextFragment
type: docs
weight: 90
url: /fr/net/aspose.pdf.text/textfragment/position/
---
## Propriété TextFragment.Position

Obtient ou définit la position du texte pour le texte, représenté par l'objet [`TextFragment`](../).

```csharp
public Position Position { get; set; }
```

## Exemples

L'exemple démontre comment visualiser le placement d'un texte, représenté par l'objet [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View text and placement info of first text occurrence
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### Voir aussi

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextSegment](../../textsegment/)
* classe [Position](../../position/)
* classe [TextFragment](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)