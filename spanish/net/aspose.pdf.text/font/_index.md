---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.Font. Representa objeto de fuente
type: docs
weight: 10510
url: /es/net/aspose.pdf.text/font/
---
## Clase Fuente

Representa objeto de fuente.

```csharp
public sealed class Font
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Obtiene el valor BaseFont del objeto fuente PDF. También conocido como el nombre PostScript de la fuente. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | A veces las fuentes PDF (generalmente fuentes chinas/japonesas/coreanas) pueden tener un nombre de fuente específico. Este nombre es el valor de la propiedad "BaseFont" de la fuente PDF y a veces esta propiedad puede estar representada en forma hexadecimal. Si se lee este nombre directamente, puede estar representado en una forma no legible. Para obtener una forma legible, es necesario decodificar el nombre de la fuente según las reglas específicas para esta fuente. Esta propiedad devuelve el nombre de fuente decodificado, así que úsala para los casos en que te encuentres con un [`FontName`](./fontname/) no legible. Si la propiedad [`FontName`](./fontname/) tiene una forma legible, esta propiedad será la misma que [`FontName`](./fontname/), por lo que puedes usar esta propiedad para cualquier caso en que necesites obtener el nombre de la fuente en una forma legible. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Obtiene el nombre de la fuente del objeto `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Propiedades útiles para ajustar el comportamiento de la fuente |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Obtiene un indicador de si la fuente está presente (instalada) en el sistema. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Obtiene o establece un valor que indica si la fuente está incrustada. La fuente basada en IFont se subconjuntará e incrustará automáticamente |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Obtiene o establece un valor que indica si la fuente es un subconjunto. La fuente basada en IFont se subconjuntará e incrustará automáticamente |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | El objetivo de este método es devolver la descripción del error si se falló en el intento de incrustar la fuente. Si no hay casos de error, devuelve una cadena vacía. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Mide la cadena. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Guarda la fuente en el flujo. Ten en cuenta que la fuente se guarda en un formato TTF intermedio destinado a ser utilizado solo en una copia convertida del documento original. El archivo de fuente no está destinado a ser utilizado fuera del contexto del documento original. |

## Ejemplos

El ejemplo demuestra cómo buscar texto en la primera página y cambiar la fuente de la primera ocurrencia de búsqueda.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Véase También

* clase [TextFragmentAbsorber](../textfragmentabsorber/)
* clase [FontRepository](../fontrepository/)
* clase [Document](../../aspose.pdf/document/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../)