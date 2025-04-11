---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Propiedad TextFragmentAbsorber. Obtiene o establece opciones de búsqueda. Las opciones permiten la búsqueda utilizando expresiones regulares
type: docs
weight: 110
url: /es/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## Propiedad TextFragmentAbsorber.TextSearchOptions

Obtiene o establece opciones de búsqueda. Las opciones permiten la búsqueda utilizando expresiones regulares.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo realizar una búsqueda de texto utilizando expresiones regulares.

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

### Ver También

* clase [TextSearchOptions](../../textsearchoptions/)
* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)