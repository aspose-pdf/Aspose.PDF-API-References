---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextFragmentAbsorber. Obtém a coleção de ocorrências de pesquisa que são apresentadas com objetos TextFragment
type: docs
weight: 90
url: /pt/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## Propriedade TextFragmentAbsorber.TextFragments

Obtém a coleção de ocorrências de pesquisa que são apresentadas com objetos [`TextFragment`](../../textfragment/).

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Exemplos

O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir todas as ocorrências de pesquisa por novo texto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Veja Também

* classe [TextFragmentCollection](../../textfragmentcollection/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)