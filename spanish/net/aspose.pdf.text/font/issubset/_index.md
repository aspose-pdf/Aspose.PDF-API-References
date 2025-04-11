---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de fuente. Obtiene o establece un valor que indica si la fuente es un subconjunto. La fuente basada en IFont se convertirá automáticamente en un subconjunto y se incrustará
type: docs
weight: 70
url: /es/net/aspose.pdf.text/font/issubset/
---
## Propiedad Font.IsSubset

Obtiene o establece un valor que indica si la fuente es un subconjunto. La fuente basada en IFont se convertirá automáticamente en un subconjunto y se incrustará

```csharp
public bool IsSubset { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo buscar texto en la primera página y obtener el valor que indica si la fuente es un subconjunto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Ver También

* clase [TextFragmentAbsorber](../../textfragmentabsorber/)
* clase [Document](../../../aspose.pdf/document/)
* clase [Font](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)