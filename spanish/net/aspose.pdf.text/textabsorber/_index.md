---
title: TextAbsorber
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa un objeto absorbente de un texto. Realiza la extracción de texto y proporciona acceso al resultado a través deText./textabsorber/text objeto.
type: docs
weight: 6960
url: /es/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

Representa un objeto absorbente de un texto. Realiza la extracción de texto y proporciona acceso al resultado a través de[`Text`](./text) objeto.

```csharp
public class TextAbsorber
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextAbsorber](textabsorber#constructor)() | Inicializa una nueva instancia del[`TextAbsorber`](../textabsorber) . |
| [TextAbsorber](textabsorber#constructor_1)(TextExtractionOptions) | Inicializa una nueva instancia del[`TextAbsorber`](../textabsorber) con opciones de extracción. |
| [TextAbsorber](textabsorber#constructor_3)(TextSearchOptions) | Inicializa una nueva instancia del[`TextAbsorber`](../textabsorber) con opciones de búsqueda de texto. |
| [TextAbsorber](textabsorber#constructor_2)(TextExtractionOptions, TextSearchOptions) | Inicializa una nueva instancia del[`TextAbsorber`](../textabsorber) con opciones de extracción y búsqueda de texto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors) { get; } | Lista de[`TextExtractionError`](../textextractionerror) objetos. Contiene información sobre errores encontrados durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; Y puede disminuir el rendimiento. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions) { get; set; } | Obtiene o establece opciones de extracción de texto. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors) { get; } | El valor indica si se encontraron errores durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; Y puede disminuir el rendimiento. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text) { get; } | Obtiene el texto extraído que el[`TextAbsorber`](../textabsorber) extractos en el documento o página PDF. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions) { get; set; } | Obtiene o establece opciones de búsqueda de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit#visit)(Document) | Extrae texto en el documento especificado |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit#visit_1)(Page) | Extrae texto en la página especificada |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit#visit_2)(XForm) | Extrae texto en el XForm especificado. |

### Observaciones

El[`TextAbsorber`](../textabsorber) El objeto se utiliza para extraer texto de un documento PDF o de la página del documento.

### Ejemplos

El ejemplo muestra cómo extraer texto en la primera página del documento PDF.

```csharp
// abrir documento
Document doc = new Document(inFile);

// crea un objeto TextAbsorber para extraer texto
TextAbsorber absorber = new TextAbsorber();

// aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// obtener el texto extraído
string extractedText = absorber.Text;

```

### Ver también

* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->