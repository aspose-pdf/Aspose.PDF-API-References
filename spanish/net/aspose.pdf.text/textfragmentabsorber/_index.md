---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.TextFragmentAbsorber. Representa un objeto absorbente de fragmentos de texto. Realiza búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección TextFragments
type: docs
weight: 10950
url: /es/net/aspose.pdf.text/textfragmentabsorber/
---
## Clase TextFragmentAbsorber

Representa un objeto absorbente de fragmentos de texto. Realiza búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección [`TextFragments`](./textfragments/).

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Inicializa una nueva instancia de `TextFragmentAbsorber` que realiza la búsqueda de todos los segmentos de texto del documento o página. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Inicializa una nueva instancia de la clase `TextFragmentAbsorber` para el objeto de clase System.Text.RegularExpressions.Regex especificado. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Inicializa una nueva instancia de la clase `TextFragmentAbsorber` para la frase de texto especificada. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Inicializa una nueva instancia de la clase `TextFragmentAbsorber` con opciones de edición de texto, que realiza la búsqueda de todos los segmentos de texto del documento o página. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Inicializa una nueva instancia de la clase `TextFragmentAbsorber` para la frase de texto especificada y opciones de edición de texto. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Inicializa una nueva instancia de la clase `TextFragmentAbsorber` para la frase de texto especificada y opciones de búsqueda de texto. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Inicializa una nueva instancia de la clase `TextFragmentAbsorber` para la frase de texto especificada y opciones de búsqueda de texto. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Inicializa una nueva instancia de la clase `TextFragmentAbsorber` para la frase de texto especificada y opciones de edición de texto. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Inicializa una nueva instancia de la clase `TextFragmentAbsorber` para la frase de texto especificada y opciones de búsqueda de texto. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Inicializa una nueva instancia de la clase `TextFragmentAbsorber` para la frase de texto especificada, opciones de búsqueda de texto y opciones de edición de texto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Lista de objetos [`TextExtractionError`](../textextractionerror/). Contiene información sobre los errores encontrados durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Obtiene o establece las opciones de extracción de texto. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Valor que indica si se encontraron errores durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Obtiene o establece la frase que el `TextFragmentAbsorber` busca en el documento o página PDF. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Obtiene un diccionario de ocurrencias de búsqueda que se presentan con la clase System.Text.RegularExpressions.Regex como clave y [`TextFragment`](../textfragment/) como valor. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Obtiene el texto extraído que el [`TextAbsorber`](../textabsorber/) extrae en el documento o página PDF. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Obtiene o establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no se puede escribir con la fuente. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos [`TextFragment`](../textfragment/). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Obtiene o establece las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto/largo. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Obtiene o establece las opciones de búsqueda. Las opciones permiten la búsqueda utilizando expresiones regulares. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Aplica el tamaño de fuente a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que recorrer los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario, funciona de manera similar a recorrer. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Aplica la fuente a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que recorrer los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario, funciona de manera similar a recorrer. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Aplica la fuente y el tamaño a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que recorrer los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario, funciona de manera similar a recorrer. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Elimina todo el texto del documento. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Elimina todo el texto de la página especificada. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Elimina el texto dentro del rectángulo especificado de la página especificada. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Limpia la colección TextFragments de este objeto `TextFragmentAbsorber`. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Realiza la búsqueda en el documento especificado. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Realiza la búsqueda en la página especificada. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Realiza la búsqueda en el objeto de formulario especificado. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Extrae texto en el XForm especificado. |

## Observaciones

El objeto `TextFragmentAbsorber` se utiliza básicamente en escenarios de búsqueda de texto. Cuando se completa la búsqueda, las ocurrencias se representan con objetos [`TextFragment`](../textfragment/) que contiene la colección [`TextFragments`](./textfragments/). El objeto [`TextFragment`](../textfragment/) proporciona acceso al texto de la ocurrencia de búsqueda, propiedades del texto y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc.).

## Ejemplos

El ejemplo demuestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver También

* clase [TextAbsorber](../textabsorber/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../)