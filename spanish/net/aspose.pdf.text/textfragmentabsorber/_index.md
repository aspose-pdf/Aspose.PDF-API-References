---
title: TextFragmentAbsorber
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa un objeto absorbente de fragmentos de texto. Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda a través deTextFragments./textfragmentabsorber/textfragments colección.
type: docs
weight: 7110
url: /es/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Representa un objeto absorbente de fragmentos de texto. Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda a través de[`TextFragments`](./textfragments) colección.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber#constructor)() | Inicializa una nueva instancia del[`TextFragmentAbsorber`](../textfragmentabsorber) que realiza la búsqueda de todos los segmentos de texto del documento o página. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_6)(Regex) | Inicializa una nueva instancia del[`TextFragmentAbsorber`](../textfragmentabsorber) clase para el objeto de clase System.Text.RegularExpressions.Regex especificado. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_2)(string) | Inicializa una nueva instancia del[`TextFragmentAbsorber`](../textfragmentabsorber) clase para la frase de texto especificada. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_1)(TextEditOptions) | Inicializa una nueva instancia del[`TextFragmentAbsorber`](../textfragmentabsorber)con opciones de edición de texto, que realiza la búsqueda de todos los segmentos de texto del documento o página. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_7)(Regex, TextEditOptions) | Inicializa una nueva instancia del[`TextFragmentAbsorber`](../textfragmentabsorber) clase para la frase de texto especificada y las opciones de edición de texto. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_8)(Regex, TextSearchOptions) | Inicializa una nueva instancia del[`TextFragmentAbsorber`](../textfragmentabsorber) clase para la frase de texto especificada y las opciones de búsqueda de texto. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_3)(string, TextEditOptions) | Inicializa una nueva instancia del[`TextFragmentAbsorber`](../textfragmentabsorber) clase para la frase de texto especificada y las opciones de edición de texto. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_4)(string, TextSearchOptions) | Inicializa una nueva instancia del[`TextFragmentAbsorber`](../textfragmentabsorber)clase para la frase de texto especificada y las opciones de búsqueda de texto. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_5)(string, TextSearchOptions, TextEditOptions) | Inicializa una nueva instancia del[`TextFragmentAbsorber`](../textfragmentabsorber) clase para la frase de texto especificada, opciones de búsqueda de texto y opciones de edición de texto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors) { get; } | Lista de[`TextExtractionError`](../textextractionerror) objetos. Contiene información sobre errores encontrados durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; Y puede disminuir el rendimiento. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions) { get; set; } | Obtiene o establece opciones de extracción de texto. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors) { get; } | El valor indica si se encontraron errores durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; Y puede disminuir el rendimiento. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase) { get; set; } | Obtiene o establece la frase que el[`TextFragmentAbsorber`](../textfragmentabsorber) búsquedas en el documento o página PDF. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text) { get; } | Obtiene el texto extraído que el[`TextAbsorber`](../textabsorber) extractos en el documento o página PDF. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions) { get; set; } | Obtiene o establece opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no se puede escribir con font. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments) { get; set; } | Obtiene una colección de instancias de búsqueda que se presentan con[`TextFragment`](../textfragment) objetos. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions) { get; set; } | Obtiene o establece opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por más corto/largo. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions) { get; set; } | Obtiene o establece las opciones de búsqueda. Las opciones habilitan la búsqueda usando expresiones regulares. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_2)(float) | Aplica el tamaño de fuente para todos los fragmentos de texto que se absorbieron. Funciona más rápido que recorrer los fragmentos si se absorbieran todos los fragmentos de la(s) página(s). De lo contrario, funciona de manera similar con looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments)(Font) | Aplica fuente para todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que recorrer los fragmentos si se absorbieran todos los fragmentos de la(s) página(s). De lo contrario, funciona de manera similar con looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_1)(Font, float) | Aplica fuente y tamaño para todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que recorrer los fragmentos si se absorbieran todos los fragmentos de la(s) página(s). De lo contrario, funciona de manera similar con looping. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext)(Document) | Elimina todo el texto del documento. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_1)(Page) | Elimina todo el texto de la página especificada. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_2)(Page, Rectangle) | Elimina el texto dentro del rectángulo especificado de la página especificada. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset)() | Borra la colección TextFragments de este[`TextFragmentAbsorber`](../textfragmentabsorber) objeto. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit)(Document) | Realiza la búsqueda en el documento especificado. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_1)(Page) | Realiza la búsqueda en la página especificada. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_2)(XForm) | Realiza la búsqueda en el objeto de formulario especificado. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit)(XForm) | Extrae texto en el XForm especificado. |

### Observaciones

El[`TextFragmentAbsorber`](../textfragmentabsorber) El objeto se usa básicamente en el escenario de búsqueda de texto. Cuando se completa la búsqueda, las ocurrencias se representan con[`TextFragment`](../textfragment) objetos que el[`TextFragments`](./textfragments) colección contiene. El[`TextFragment`](../textfragment) El objeto proporciona acceso al texto de ocurrencia de búsqueda, las propiedades del texto y permite editar el texto y cambiar el estado del texto (fuente, tamaño de fuente, color, etc.).

### Ejemplos

El ejemplo demuestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Encuentra la fuente que se usará para cambiar la fuente del texto del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crear objeto TextFragmentAbsorber para encontrar todas las apariciones de texto "hola mundo"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// Cambia el texto y la fuente de la primera aparición de texto
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver también

* class [TextAbsorber](../textabsorber)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
