---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextFragmentAbsorber. Obtém ou define opções de pesquisa. As opções permitem a pesquisa usando expressões regulares
type: docs
weight: 110
url: /pt/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## Propriedade TextFragmentAbsorber.TextSearchOptions

Obtém ou define opções de pesquisa. As opções permitem a pesquisa usando expressões regulares.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Exemplos

O exemplo demonstra como realizar a pesquisa de texto usando expressões regulares.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Veja Também

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)