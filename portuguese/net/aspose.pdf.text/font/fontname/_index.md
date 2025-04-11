---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Propriedade Font. Obtém o nome da fonte do objeto Font
type: docs
weight: 30
url: /pt/net/aspose.pdf.text/font/fontname/
---
## Propriedade Font.FontName

Obtém o nome da fonte do [`Font`](../) objeto.

```csharp
public string FontName { get; }
```

## Exemplos

O exemplo demonstra como pesquisar texto na primeira página e visualizar o nome da fonte da primeira ocorrência de texto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### Veja Também

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)