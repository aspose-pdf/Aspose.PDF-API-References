---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextFragmentAbsorber. Obtém ou define a frase que o TextFragmentAbsorber procura no documento ou página PDF
type: docs
weight: 50
url: /pt/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## Propriedade TextFragmentAbsorber.Phrase

Obtém ou define a frase que o [`TextFragmentAbsorber`](../) procura no documento ou página PDF.

```csharp
public string Phrase { get; set; }
```

## Exemplos

O exemplo demonstra como realizar a busca de texto várias vezes e realizar substituições de texto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Veja Também

* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)