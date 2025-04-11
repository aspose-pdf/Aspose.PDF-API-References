---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de fuente. Obtiene el nombre de la fuente del objeto Font
type: docs
weight: 30
url: /es/net/aspose.pdf.text/font/fontname/
---
## Propiedad Font.FontName

Obtiene el nombre de la fuente del objeto [`Font`](../).

```csharp
public string FontName { get; }
```

## Ejemplos

El ejemplo demuestra cómo buscar texto en la primera página y ver el nombre de la fuente de la primera ocurrencia de texto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### Ver También

* clase [TextFragmentAbsorber](../../textfragmentabsorber/)
* clase [Document](../../../aspose.pdf/document/)
* clase [Font](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)