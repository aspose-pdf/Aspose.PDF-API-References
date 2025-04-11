---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.TextAbsorber. Representa un objeto absorbente de texto. Realiza la extracción de texto y proporciona acceso al resultado a través del objeto [`Text`](./text/).
type: docs
weight: 10800
url: /es/net/aspose.pdf.text/textabsorber/
---
## Clase TextAbsorber

Representa un objeto absorbente de texto. Realiza la extracción de texto y proporciona acceso al resultado a través del objeto [`Text`](./text/).

```csharp
public class TextAbsorber
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Inicializa una nueva instancia de `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Inicializa una nueva instancia de `TextAbsorber` con opciones de extracción. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Inicializa una nueva instancia de `TextAbsorber` con opciones de búsqueda de texto. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Inicializa una nueva instancia de `TextAbsorber` con opciones de extracción y búsqueda de texto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Lista de objetos [`TextExtractionError`](../textextractionerror/). Contiene información sobre los errores encontrados durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Obtiene o establece las opciones de extracción de texto. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | El valor indica si se encontraron errores durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Obtiene el texto extraído que el `TextAbsorber` extrae del documento o página PDF. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Obtiene o establece las opciones de búsqueda de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Extrae texto del documento especificado |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Extrae texto de la página especificada |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Extrae texto del XForm especificado. |

## Observaciones

El objeto `TextAbsorber` se utiliza para extraer texto de un documento Pdf o de la página del documento.

## Ejemplos

El ejemplo demuestra cómo extraer texto de la primera página del documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Véase También

* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../)