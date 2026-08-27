---
title: "TextFragment.Segments"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextFragment-egenskap. Hämtar textsegment för aktuellt TextFragment."
type: docs
weight: 120
url: /sv/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments property

Hämtar textsegment för aktuellt [`TextFragment`](../).

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Anmärkningar

Med några ord är [`TextSegment`](../../textsegment/)-objekt barn till [`TextFragment`](../)-objektet. Avancerade användare kan komma åt segmenten direkt för att utföra mer komplexa textredigeringsscenarier. För detaljer, se beskrivningen av [`TextFragment`](../)-objektet.

## Exempel

Exemplet visar hur man navigerar alla [`TextSegment`](../../textsegment/)-objekt inuti [`TextFragment`](../).

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Navigera alla textsegment och skriv ut deras text och placeringsinformation
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


