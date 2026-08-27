---
title: "TextFragment.Position"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextFragment. Ottiene o imposta la posizione del testo per il testo rappresentato dall'oggetto TextFragment"
type: docs
weight: 90
url: /it/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position property

Ottiene o imposta la posizione del testo per il testo, rappresentato dall'oggetto [`TextFragment`](../).

```csharp
public Position Position { get; set; }
```

## Esempi

L'esempio dimostra come visualizzare il posizionamento di un testo, rappresentato dall'oggetto [`TextFragment`](../).

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Visualizza il testo e le informazioni di posizionamento della prima occorrenza di testo
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### Vedi anche

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [Position](../../position/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


