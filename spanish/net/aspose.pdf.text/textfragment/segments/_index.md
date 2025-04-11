---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de TextFragment. Obtiene segmentos de texto para el TextFragment actual
type: docs
weight: 120
url: /es/net/aspose.pdf.text/textfragment/segments/
---
## Propiedad TextFragment.Segments

Obtiene segmentos de texto para el [`TextFragment`](../) actual.

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Observaciones

En pocas palabras, los objetos [`TextSegment`](../../textsegment/) son hijos del objeto [`TextFragment`](../). Los usuarios avanzados pueden acceder a los segmentos directamente para realizar escenarios de edición de texto más complejos. Para más detalles, consulte la descripción del objeto [`TextFragment`](../).

## Ejemplos

El ejemplo demuestra cómo navegar por todos los objetos [`TextSegment`](../../textsegment/) dentro de [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Navigate all text segments and out their text and placement info
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### Véase también

* clase [TextFragmentAbsorber](../../textfragmentabsorber/)
* clase [Document](../../../aspose.pdf/document/)
* clase [TextSegment](../../textsegment/)
* clase [TextSegmentCollection](../../textsegmentcollection/)
* clase [TextFragment](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)