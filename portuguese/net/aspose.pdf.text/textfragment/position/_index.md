---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextFragment. Obtém ou define a posição do texto para o texto representado com o objeto TextFragment
type: docs
weight: 90
url: /pt/net/aspose.pdf.text/textfragment/position/
---
## Propriedade TextFragment.Position

Obtém ou define a posição do texto para o texto, representado pelo objeto [`TextFragment`](../).

```csharp
public Position Position { get; set; }
```

## Exemplos

O exemplo demonstra como visualizar a colocação de um texto, representado pelo objeto [`TextFragment`](../).

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

### Veja Também

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextSegment](../../textsegment/)
* classe [Position](../../position/)
* classe [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)