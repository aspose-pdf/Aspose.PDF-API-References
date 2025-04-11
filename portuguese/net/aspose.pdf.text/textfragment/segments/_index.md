---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextFragment. Obtém segmentos de texto para o TextFragment atual
type: docs
weight: 120
url: /pt/net/aspose.pdf.text/textfragment/segments/
---
## Propriedade TextFragment.Segments

Obtém segmentos de texto para o [`TextFragment`](../) atual.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Observações

Em poucas palavras, os objetos [`TextSegment`](../../textsegment/) são filhos do objeto [`TextFragment`](../). Usuários avançados podem acessar segmentos diretamente para realizar cenários de edição de texto mais complexos. Para detalhes, consulte a descrição do objeto [`TextFragment`](../).

## Exemplos

O exemplo demonstra como navegar por todos os objetos [`TextSegment`](../../textsegment/) dentro do [`TextFragment`](../).

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

### Veja Também

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextSegment](../../textsegment/)
* classe [TextSegmentCollection](../../textsegmentcollection/)
* classe [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)