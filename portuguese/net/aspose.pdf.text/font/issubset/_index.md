---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Propriedade da fonte. Obtém ou define um valor que indica se a fonte é um subconjunto. Fontes baseadas em IFont serão automaticamente subconjuntos e incorporadas
type: docs
weight: 70
url: /pt/net/aspose.pdf.text/font/issubset/
---
## Propriedade Font.IsSubset

Obtém ou define um valor que indica se a fonte é um subconjunto. Fontes baseadas em IFont serão automaticamente subconjuntos e incorporadas

```csharp
public bool IsSubset { get; set; }
```

## Exemplos

O exemplo demonstra como pesquisar texto na primeira página e obter o valor que indica se a fonte é um subconjunto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Veja Também

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)