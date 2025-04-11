---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: Propiedad TextFragment. Obtiene o establece el estado del texto para el texto que representa el objeto TextFragment
type: docs
weight: 150
url: /es/net/aspose.pdf.text/textfragment/textstate/
---
## Propiedad TextFragment.TextState

Obtiene o establece el estado del texto para el texto que representa el objeto [`TextFragment`](../).

```csharp
public TextFragmentState TextState { get; }
```

## Observaciones

Proporciona una forma de cambiar las siguientes propiedades del texto: Fuente TamañoDeFuente EstiloDeFuente ColorDePrimerPlano ColorDeFondo

## Ejemplos

El ejemplo demuestra cómo cambiar el color del texto y el tamaño de la fuente del texto con el objeto `TextState`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver También

* clase [TextFragmentAbsorber](../../textfragmentabsorber/)
* clase [Document](../../../aspose.pdf/document/)
* clase [TextFragmentState](../../textfragmentstate/)
* clase [TextFragment](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)