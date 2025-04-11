---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: Propiedad TextFragmentAbsorber. Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos TextFragment
type: docs
weight: 90
url: /es/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## Propiedad TextFragmentAbsorber.TextFragments

Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos [`TextFragment`](../../textfragment/).

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo encontrar texto en la primera página del documento PDF y reemplazar todas las ocurrencias de búsqueda con nuevo texto.

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

### Ver También

* clase [TextFragmentCollection](../../textfragmentcollection/)
* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)