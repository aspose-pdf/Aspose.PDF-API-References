---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: Proprietà TextFragment. Ottiene segmenti di testo per l'attuale TextFragment
type: docs
weight: 120
url: /it/net/aspose.pdf.text/textfragment/segments/
---
## Proprietà TextFragment.Segments

Ottiene segmenti di testo per l'attuale [`TextFragment`](../).

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Osservazioni

In poche parole, gli oggetti [`TextSegment`](../../textsegment/) sono figli dell'oggetto [`TextFragment`](../). Gli utenti avanzati possono accedere ai segmenti direttamente per eseguire scenari di modifica del testo più complessi. Per ulteriori dettagli, si prega di consultare la descrizione dell'oggetto [`TextFragment`](../).

## Esempi

L'esempio dimostra come navigare tra tutti gli oggetti [`TextSegment`](../../textsegment/) all'interno di [`TextFragment`](../).

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

### Vedi Anche

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextSegment](../../textsegment/)
* classe [TextSegmentCollection](../../textsegmentcollection/)
* classe [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)