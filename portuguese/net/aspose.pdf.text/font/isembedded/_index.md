---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: Propriedade da fonte. Obtém ou define um valor que indica se a fonte está incorporada. Fontes baseadas em IFont serão automaticamente subconjuntadas e incorporadas
type: docs
weight: 60
url: /pt/net/aspose.pdf.text/font/isembedded/
---
## Propriedade Font.IsEmbedded

Obtém ou define um valor que indica se a fonte está incorporada. Fontes baseadas em IFont serão automaticamente subconjuntadas e incorporadas

```csharp
public bool IsEmbedded { get; set; }
```

## Exemplos

O exemplo a seguir demonstra como encontrar uma fonte, marcá-la como incorporada, pesquisar texto na página do documento e substituir a fonte do texto.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Veja Também

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)