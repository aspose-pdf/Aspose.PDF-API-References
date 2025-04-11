---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de fuente. Obtiene un indicador de si la fuente está instalada en el sistema
type: docs
weight: 50
url: /es/net/aspose.pdf.text/font/isaccessible/
---
## Propiedad Font.IsAccessible

Obtiene un indicador de si la fuente está presente (instalada) en el sistema.

```csharp
public bool IsAccessible { get; }
```

## Observaciones

Algunas operaciones no están disponibles con fuentes que no se pudieron encontrar en el sistema.

## Ejemplos

El ejemplo demuestra cómo buscar texto en la primera página y obtener el valor que indica si la fuente está instalada en el sistema.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### Ver También

* clase [TextFragmentAbsorber](../../textfragmentabsorber/)
* clase [Document](../../../aspose.pdf/document/)
* clase [Font](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)