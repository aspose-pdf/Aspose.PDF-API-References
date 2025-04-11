---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextFragment. Obtém ou define o objeto de texto String que o objeto TextFragment representa
type: docs
weight: 130
url: /pt/net/aspose.pdf.text/textfragment/text/
---
## Propriedade TextFragment.Text

Obtém ou define o objeto de texto String que o [`TextFragment`](../) representa.

```csharp
public string Text { get; set; }
```

## Exemplos

O exemplo demonstra como pesquisar um texto e substituir a primeira ocorrência representada pelo objeto [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Veja Também

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)