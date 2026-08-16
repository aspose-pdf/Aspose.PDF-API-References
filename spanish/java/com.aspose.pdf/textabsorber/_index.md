---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa un objeto absorbente de texto. Realiza la extracción de texto y proporciona acceso al resultado a través del objeto {@code TextAbsorber.Text}. </p> <hr> <pre> El ejemplo.</pre>"
type: docs
weight: 4900
url: /es/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> Representa un objeto absorbente de texto. Realiza la extracción de texto y proporciona acceso al resultado mediante el objeto {@code TextAbsorber.Text}. </p> <hr> <pre> El ejemplo muestra cómo extraer texto en la primera página del documento PDF.\n// abrir documento Document doc = new Document(inFile);\n// crear objeto TextAbsorber para extraer texto TextAbsorber absorber = new TextAbsorber();\n// aceptar el absorbente para la primera página doc.getPages().get(1).accept(absorber);\n// obtener el texto extraído String extractedText = absorber.getText();\n</pre> <hr> <p> El objeto {@code TextAbsorber} se usa para extraer texto de un documento Pdf o de la página del documento. </p>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> Inicializa una nueva instancia de {@code TextAbsorber}. </p> <hr> <pre> El ejemplo muestra cómo extraer texto de todas las páginas del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> Inicializa una nueva instancia de {@code TextAbsorber}. </p> <hr> <pre> El ejemplo muestra cómo extraer texto de todas las páginas del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa una nueva instancia de {@code TextAbsorber}. </p> <hr> <pre> El ejemplo muestra cómo extraer texto de todas las páginas del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa una nueva instancia de {@code TextAbsorber}. </p> <hr> <pre> El ejemplo muestra cómo extraer texto de todas las páginas del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto {@code TextAbsorber.Text}. </p> |

## Métodos

| Método | Descripción |
| --- | --- |
| [getErrors](#getErrors--) | Lista de objetos {@code TextExtractionError}. Contiene información sobre los errores encontrados durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| [getExtractionOptions](#getExtractionOptions--) | <p> Obtiene las opciones de extracción de texto. </p> <hr> <pre> El ejemplo muestra cómo establecer el modo de formato de texto puro y realizar la extracción de texto. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permite definir el modo de formato de texto {@code TextExtractionOptions} durante la extracción. El modo predeterminado es {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [getText](#getText--) | <p> Obtiene el texto extraído que {@code TextAbsorber} extrae del documento PDF o página. </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | Obtiene las opciones de búsqueda de texto. Permite definir un rectángulo que delimita el texto extraído. Por defecto el rectángulo está vacío. Eso significa que solo los límites de la página definen la región de extracción de texto. |
| [hasErrors](#hasErrors--) | El valor indica si se encontraron errores durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Establece las opciones de extracción de texto. </p> <hr> <pre> El ejemplo muestra cómo establecer el modo de formato de texto puro y realizar la extracción de texto. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permite definir el modo de formato de texto {@code TextExtractionOptions} durante la extracción. El modo predeterminado es {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Establece las opciones de búsqueda de texto. Permite definir un rectángulo que delimita el texto extraído. Por defecto el rectángulo está vacío. Eso significa que solo los límites de la página definen la región de extracción de texto. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extrae texto del documento especificado </p> <hr> <pre> El ejemplo muestra cómo extraer texto de un documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extrae texto de la página especificada </p> <hr> <pre> El ejemplo muestra cómo extraer texto de la primera página del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> Extrae texto del XForm especificado. </p> <hr> <pre> El ejemplo muestra cómo extraer texto de la primera página del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // get the extracted text String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> Inicializa una nueva instancia de {@code TextAbsorber}. </p> <hr> <pre> El ejemplo muestra cómo extraer texto de todas las páginas del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> Inicializa una nueva instancia de {@code TextAbsorber}. </p> <hr> <pre> El ejemplo muestra cómo extraer texto de todas las páginas del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa una nueva instancia de {@code TextAbsorber}. </p> <hr> <pre> El ejemplo muestra cómo extraer texto de todas las páginas del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa una nueva instancia de {@code TextAbsorber}. </p> <hr> <pre> El ejemplo muestra cómo extraer texto de todas las páginas del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Realiza la extracción de texto y proporciona acceso al texto extraído a través del objeto {@code TextAbsorber.Text}. </p>

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

<p> Obtiene las opciones de extracción de texto. </p> <hr> <pre> El ejemplo muestra cómo establecer el modo de formato de texto puro y realizar la extracción de texto. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permite definir el modo de formato de texto {@code TextExtractionOptions} durante la extracción. El modo predeterminado es {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

**Returns:**
Valor de TextExtractionOptions

### getText {#getText--}
```
public String getText()
```

<p> Obtiene el texto extraído que {@code TextAbsorber} extrae del documento PDF o página. </p>

**Returns:**
String value <hr> <pre> El ejemplo muestra cómo extraer texto de todas las páginas del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Obtiene las opciones de búsqueda de texto. Permite definir un rectángulo que delimita el texto extraído. Por defecto el rectángulo está vacío. Eso significa que solo los límites de la página definen la región de extracción de texto.

**Returns:**
Valor de TextSearchOptions

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

El valor indica si se encontraron errores durante la extracción de texto. La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento.

**Returns:**
valor booleano

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Establece las opciones de extracción de texto. </p> <hr> <pre> El ejemplo muestra cómo establecer el modo de formato de texto puro y realizar la extracción de texto. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permite definir el modo de formato de texto {@code TextExtractionOptions} durante la extracción. El modo predeterminado es {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Establece las opciones de búsqueda de texto. Permite definir un rectángulo que delimita el texto extraído. Por defecto el rectángulo está vacío. Eso significa que solo los límites de la página definen la región de extracción de texto.

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extrae texto del documento especificado </p> <hr> <pre> El ejemplo muestra cómo extraer texto de un documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extrae texto de la página especificada </p> <hr> <pre> El ejemplo muestra cómo extraer texto de la primera página del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> Extrae texto del XForm especificado. </p> <hr> <pre> El ejemplo muestra cómo extraer texto de la primera página del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // get the extracted text String extractedText = absorber.getText(); </pre>
