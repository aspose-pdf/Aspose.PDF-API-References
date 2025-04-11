---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.ParagraphAbsorber. Representa un objeto absorbente de objetos de estructura de página como secciones y párrafos. Realiza la búsqueda de secciones y párrafos de texto y proporciona acceso a rectángulos y poliedros que lo describen en el espacio de coordenadas de texto. También realiza la búsqueda de segmentos de texto y proporciona acceso a los resultados de búsqueda a través de colecciones de TextFragments agrupadas por elementos de estructura.
type: docs
weight: 10670
url: /es/net/aspose.pdf.text/paragraphabsorber/
---
## Clase ParagraphAbsorber

Representa un objeto absorbente de objetos de estructura de página como secciones y párrafos. Realiza la búsqueda de secciones y párrafos de texto y proporciona acceso a rectángulos y poliedros que lo describen en el espacio de coordenadas de texto. También realiza la búsqueda de segmentos de texto y proporciona acceso a los resultados de búsqueda a través de colecciones de !:TextFragments agrupadas por elementos de estructura.

```csharp
public class ParagraphAbsorber
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Inicializa una nueva instancia de `ParagraphAbsorber` que realiza la búsqueda de secciones/párrafos del documento o página. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Inicializa una nueva instancia de `ParagraphAbsorber` que realiza la búsqueda de secciones/párrafos del documento o página. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Inicializa una nueva instancia de `ParagraphAbsorber` que realiza la búsqueda de secciones/párrafos del documento o página con los parámetros especificados. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Inicializa una nueva instancia de `ParagraphAbsorber` que realiza la búsqueda de secciones/párrafos del documento o página con los parámetros especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Obtiene o establece el valor que indica si las líneas de texto iniciales de una sección siguiente pueden ser tratadas como continuación del último párrafo de una sección anterior. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Obtiene la colección de [`PageMarkup`](../pagemarkup/) que fueron absorbidos. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Obtiene o establece las opciones de ParagraphAbsorber. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Obtiene o establece el valor que indica cuántas veces se realizarán búsquedas secuenciales para elementos de estructura más finos. La profundidad de búsqueda predeterminada es 3. Esto significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para secciones divididas verticalmente (columnas). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Obtiene o establece las opciones de TextReplace. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Realiza la búsqueda de secciones y párrafos en el [`Document`](../../aspose.pdf/document/) especificado. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Realiza la búsqueda en la [`Page`](../../aspose.pdf/page/) especificada. |

## Observaciones

Cuando se completa la búsqueda, la colección [`PageMarkups`](./pagemarkups/) contendrá objetos [`PageMarkup`](../pagemarkup/) que representan la estructura de la página mediante colecciones de [`MarkupSection`](../markupsection/) y [`MarkupParagraph`](../markupparagraph/). El objeto [`TextFragment`](../textfragment/) proporciona acceso al texto de ocurrencia de búsqueda, propiedades de texto y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc.).

## Ejemplos

El ejemplo demuestra cómo encontrar el primer segmento de texto de cada párrafo en la primera página del documento PDF y resaltarlo.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### Ver También

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)