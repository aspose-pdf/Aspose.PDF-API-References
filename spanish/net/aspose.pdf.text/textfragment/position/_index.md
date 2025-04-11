---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: Propiedad TextFragment. Obtiene o establece la posición del texto para el texto representado con el objeto TextFragment
type: docs
weight: 90
url: /es/net/aspose.pdf.text/textfragment/position/
---
## Propiedad TextFragment.Position

Obtiene o establece la posición del texto para el texto, representado con el objeto [`TextFragment`](../).

```csharp
public Position Position { get; set; }
```

## Ejemplos

El ejemplo demuestra cómo ver la colocación de un texto, representado por el objeto [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View text and placement info of first text occurrence
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### Véase también

* clase [TextFragmentAbsorber](../../textfragmentabsorber/)
* clase [Document](../../../aspose.pdf/document/)
* clase [TextSegment](../../textsegment/)
* clase [Position](../../position/)
* clase [TextFragment](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)