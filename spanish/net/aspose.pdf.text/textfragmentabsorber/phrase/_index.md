---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de TextFragmentAbsorber. Obtiene o establece la frase que el TextFragmentAbsorber busca en el documento o página PDF
type: docs
weight: 50
url: /es/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## Propiedad TextFragmentAbsorber.Phrase

Obtiene o establece la frase que el [`TextFragmentAbsorber`](../) busca en el documento o página PDF.

```csharp
public string Phrase { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo realizar búsquedas de texto varias veces y realizar reemplazos de texto.

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

### Ver También

* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)