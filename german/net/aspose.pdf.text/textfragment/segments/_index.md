---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: TextFragment-Eigenschaft. Holt Textsegmente für das aktuelle TextFragment
type: docs
weight: 120
url: /de/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segmente-Eigenschaft

Holt Textsegmente für das aktuelle [`TextFragment`](../).

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Anmerkungen

In wenigen Worten sind [`TextSegment`](../../textsegment/) Objekte Kinder des [`TextFragment`](../) Objekts. Fortgeschrittene Benutzer können Segmente direkt zugreifen, um komplexere Textbearbeitungsszenarien durchzuführen. Für Details siehe die Beschreibung des [`TextFragment`](../) Objekts.

## Beispiele

Das Beispiel zeigt, wie man alle [`TextSegment`](../../textsegment/) Objekte innerhalb des [`TextFragment`](../) navigiert.

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

### Siehe auch

* Klasse [TextFragmentAbsorber](../../textfragmentabsorber/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [TextSegment](../../textsegment/)
* Klasse [TextSegmentCollection](../../textsegmentcollection/)
* Klasse [TextFragment](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)