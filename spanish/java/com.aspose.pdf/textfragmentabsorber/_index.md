---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa un objeto absorbente de fragmentos de texto. Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>."
type: docs
weight: 5120
url: /es/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> Representa un objeto absorbente de fragmentos de texto. Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente. // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber para encontrar todas las apariciones del texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto y la fuente de la primera aparición del texto absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Guardar el documento doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> El objeto {@code TextFragmentAbsorber} se utiliza básicamente en escenarios de búsqueda de texto. Cuando la búsqueda se completa, las apariciones se representan con objetos {@code TextFragment} que contiene la colección {@code TextFragmentAbsorber.TextFragments}. El objeto {@code TextFragment} proporciona acceso al texto de la aparición buscada, a sus propiedades y permite editar el texto y cambiar su estado (fuente, tamaño de fuente, color, etc). </p>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> Inicializa una nueva instancia del {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurar el absorbente para buscar todas las apariciones del texto "hello world" absorber.setPhrase ( "hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto de la primera aparición absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> Inicializa una nueva instancia del {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurar el absorbente para buscar todas las apariciones del texto "hello world" absorber.setPhrase ( "hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto de la primera aparición absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa una nueva instancia del {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurar el absorbente para buscar todas las apariciones del texto "hello world" absorber.setPhrase ( "hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto de la primera aparición absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> Inicializa una nueva instancia del {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurar el absorbente para buscar todas las apariciones del texto "hello world" absorber.setPhrase ( "hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto de la primera aparición absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa una nueva instancia del {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurar el absorbente para buscar todas las apariciones del texto "hello world" absorber.setPhrase ( "hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto de la primera aparición absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> Inicializa una nueva instancia del {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurar el absorbente para buscar todas las apariciones del texto "hello world" absorber.setPhrase ( "hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto de la primera aparición absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> Inicializa una nueva instancia del {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurar el absorbente para buscar todas las apariciones del texto "hello world" absorber.setPhrase ( "hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto de la primera aparición absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa una nueva instancia del {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurar el absorbente para buscar todas las apariciones del texto "hello world" absorber.setPhrase ( "hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto de la primera aparición absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> Inicializa una nueva instancia del {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurar el absorbente para buscar todas las apariciones del texto "hello world" absorber.setPhrase ( "hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto de la primera aparición absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> Inicializa una nueva instancia del {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurar el absorbente para buscar todas las apariciones del texto "hello world" absorber.setPhrase ( "hello world"); // Aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el texto de la primera aparición absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de la búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p> |

## Métodos

| Método | Descripción |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | Aplica el tamaño de fuente a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario funciona de manera similar a la iteración. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | Aplica la fuente a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario funciona de manera similar a la iteración. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | Aplica la fuente y el tamaño a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario funciona de manera similar a la iteración. |
| [getErrors](#getErrors--) | Lista de objetos {@code TextExtractionError}. Contiene información sobre los errores encontrados durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| [getExtractionOptions](#getExtractionOptions--) | Obtiene las opciones de extracción de texto. |
| [getPhrase](#getPhrase--) | <p> Obtiene la frase que el {@code TextFragmentAbsorber} busca en el documento PDF o página. </p> |
| [getRegexResults](#getRegexResults--) | Obtiene el diccionario de ocurrencias de búsqueda que se presentan con la clase System.Text.RegularExpressions.Regex como clave y {@link TextFragment} como valor. El ejemplo muestra cómo encontrar texto con una matriz de expresiones regulares en la primera página del documento PDF. // Abrir documento Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Crear objeto TextFragmentAbsorber que busca todas las palabras que comienzan con 'h' y terminan con 'o' usando expresiones regulares. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Obtener resultados Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | Obtiene el texto extraído que {@code TextAbsorber} extrae en el documento PDF o página. |
| [getTextEditOptions](#getTextEditOptions--) | Obtiene las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede escribirse con la fuente. |
| [getTextFragments](#getTextFragments--) | <p> Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos {@code TextFragment}. </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Obtiene las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo. |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Obtiene las opciones de búsqueda. Las opciones habilitan la búsqueda usando expresiones regulares. </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | El valor indica si se encontraron errores durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | Elimina todo el texto del documento. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | Elimina todo el texto de la página especificada. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Elimina el texto dentro del rectángulo especificado de la página indicada. |
| [reset](#reset--) | Limpia la colección TextFragments de este objeto {@code TextFragmentAbsorber}. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Establece las opciones de extracción de texto. |
| [setPhrase](#setPhrase-java.lang.String-) | <p> Establece la frase que {@code TextFragmentAbsorber} busca en el documento PDF o página. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede escribirse con la fuente. |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> Establece la colección de ocurrencias de búsqueda que se presentan con objetos {@code TextFragment}. </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Establece las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Establece las opciones de búsqueda. Las opciones habilitan la búsqueda usando expresiones regulares. </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Realiza una búsqueda en el documento especificado. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en un documento PDF y reemplazar el texto de todas las ocurrencias de búsqueda. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceptar el absorber para la primera página absorber.visit(doc); // Cambiar el texto de la primera ocurrencia absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Realiza una búsqueda en la página especificada. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceptar el absorber para la primera página absorber.visit(doc.getPages().get(1)); // Cambiar el texto de todas las ocurrencias de búsqueda for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Guardar documento doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | Realiza una búsqueda en el objeto de formulario especificado. |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> Inicializa una nueva instancia de {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> Inicializa una nueva instancia de {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa una nueva instancia de {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> Inicializa una nueva instancia de {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa una nueva instancia de {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> Inicializa una nueva instancia de {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> Inicializa una nueva instancia de {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa una nueva instancia de {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> Inicializa una nueva instancia de {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> Inicializa una nueva instancia de {@code TextFragmentAbsorber} que realiza la búsqueda de todos los segmentos de texto del documento o página. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección {@code TextFragmentAbsorber.TextFragments}. </p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

Aplica el tamaño de fuente a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario funciona de manera similar a la iteración.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontSize |  | Tamaño de fuente del texto. |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
Aplica la fuente a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario funciona de manera similar a la iteración.

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
Aplica la fuente y el tamaño a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario funciona de manera similar a la iteración.

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Lista de objetos {@code TextExtractionError}. Contiene información sobre los errores encontrados durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento.

**Returns:**
Lista de objetos TextExtractionError

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

Obtiene las opciones de extracción de texto.

**Returns:**
Objeto TextExtractionOptions

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> Obtiene la frase que el {@code TextFragmentAbsorber} busca en el documento PDF o página. </p>

**Returns:**
Valor de cadena <hr> <pre> El ejemplo muestra cómo realizar la búsqueda de texto varias veces y efectuar reemplazos de texto. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // search another word and replace it absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

Obtiene el diccionario de ocurrencias de búsqueda que se presentan con la clase System.Text.RegularExpressions.Regex como clave y {@link TextFragment} como valor. El ejemplo muestra cómo encontrar texto con una matriz de expresiones regulares en la primera página del documento PDF. // Abrir documento Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Crear objeto TextFragmentAbsorber que busca todas las palabras que comienzan con 'h' y terminan con 'o' usando expresiones regulares. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Obtener resultados Dictionary results = absorber.getRegexResults();

**Returns:**
Instancia de Dictionary

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

Obtiene el texto extraído que {@code TextAbsorber} extrae en el documento PDF o página.

**Returns:**
Valor de cadena El ejemplo muestra cómo extraer texto de todas las páginas del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Obtiene las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede escribirse con la fuente.

**Returns:**
Objeto TextEditOptions

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos {@code TextFragment}. </p>

**Returns:**
Objeto TextFragmentCollection <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar todas las coincidencias de búsqueda con texto nuevo. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Obtiene las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo.

**Returns:**
Valor de TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Obtiene las opciones de búsqueda. Las opciones habilitan la búsqueda usando expresiones regulares. </p>

**Returns:**
Objeto TextSearchOptions <hr> <pre> El ejemplo muestra cómo realizar la búsqueda de texto usando expresiones regulares. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // make the absorber to search all words starting 'h' and ending 'o' using regular expression. absorber.setPhrase ( "h\w*?o"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // we should find "hello" word and replace it with "Hi" doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

El valor indica si se encontraron errores durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento.

**Returns:**
valor booleano

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
Elimina todo el texto del documento.

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
Elimina todo el texto de la página especificada.

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Elimina el texto dentro del rectángulo especificado de la página indicada.

### reset {#reset--}
```
public void reset()
```

Limpia la colección TextFragments de este objeto {@code TextFragmentAbsorber}.

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
Establece las opciones de extracción de texto.

### setPhrase {#setPhrase-java.lang.String-}
<p> Establece la frase que {@code TextFragmentAbsorber} busca en el documento PDF o página. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede escribirse con la fuente.

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> Establece la colección de ocurrencias de búsqueda que se presentan con objetos {@code TextFragment}. </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Establece las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Establece las opciones de búsqueda. Las opciones habilitan la búsqueda usando expresiones regulares. </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Realiza una búsqueda en el documento especificado. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en un documento PDF y reemplazar el texto de todas las ocurrencias de búsqueda. // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceptar el absorber para la primera página absorber.visit(doc); // Cambiar el texto de la primera ocurrencia absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Guardar el documento doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Realiza una búsqueda en la página especificada. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto. // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Encontrar la fuente que se usará para cambiar la fuente del texto del documento Font font = FontRepository.findFont("Arial"); // Crear el objeto TextFragmentAbsorber para encontrar todas las ocurrencias del texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceptar el absorber para la primera página absorber.visit(doc.getPages().get(1)); // Cambiar el texto de todas las ocurrencias de búsqueda for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Guardar el documento doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
Realiza una búsqueda en el objeto de formulario especificado.
