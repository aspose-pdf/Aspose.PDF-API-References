---
title: "TextFragment.Segments"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextFragment. Ottiene i segmenti di testo per l'attuale TextFragment"
type: docs
weight: 120
url: /it/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments property

Ottiene i segmenti di testo per l'attuale [`TextFragment`](../).

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Osservazioni

In poche parole, gli oggetti [`TextSegment`](../../textsegment/) sono figli dell'oggetto [`TextFragment`](../). Gli utenti esperti possono accedere direttamente ai segmenti per eseguire scenari di modifica del testo più complessi. Per i dettagli, consultare la descrizione dell'oggetto [`TextFragment`](../).

## Esempi

L'esempio dimostra come navigare tutti gli oggetti [`TextSegment`](../../textsegment/) all'interno di [`TextFragment`](../).

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Naviga tutti i segmenti di testo e visualizza il loro testo e le informazioni di posizionamento
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### Vedi anche

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


