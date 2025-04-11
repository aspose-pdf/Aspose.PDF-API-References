---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: TextFragment-Eigenschaft. Ruft die Textposition für Text ab oder setzt sie, die mit dem TextFragment-Objekt dargestellt wird
type: docs
weight: 90
url: /de/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position-Eigenschaft

Ruft die Textposition für Text ab oder setzt sie, die mit dem [`TextFragment`](../) Objekt dargestellt wird.

```csharp
public Position Position { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie die Platzierung eines Textes, dargestellt durch das [`TextFragment`](../) Objekt, angezeigt wird.

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

### Siehe auch

* Klasse [TextFragmentAbsorber](../../textfragmentabsorber/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [TextSegment](../../textsegment/)
* Klasse [Position](../../position/)
* Klasse [TextFragment](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)