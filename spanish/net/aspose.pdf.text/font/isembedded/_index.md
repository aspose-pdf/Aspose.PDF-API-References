---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de fuente. Obtiene o establece un valor que indica si la fuente está incrustada. La fuente basada en IFont se subconjuntará e incrustará automáticamente
type: docs
weight: 60
url: /es/net/aspose.pdf.text/font/isembedded/
---
## Propiedad Font.IsEmbedded

Obtiene o establece un valor que indica si la fuente está incrustada. La fuente basada en IFont se subconjuntará e incrustará automáticamente

```csharp
public bool IsEmbedded { get; set; }
```

## Ejemplos

El siguiente ejemplo demuestra cómo encontrar una fuente, marcarla como incrustada, buscar texto en la página del documento y reemplazar la fuente del texto.

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

### Ver También

* clase [TextFragmentAbsorber](../../textfragmentabsorber/)
* clase [FontRepository](../../fontrepository/)
* clase [Document](../../../aspose.pdf/document/)
* clase [Font](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)