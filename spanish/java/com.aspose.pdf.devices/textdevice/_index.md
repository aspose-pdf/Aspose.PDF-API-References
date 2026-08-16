---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa una clase para convertir páginas de documentos pdf a texto. </p> <hr> <pre> El ejemplo muestra cómo extraer texto en la primera página del documento PDF. Document doc = new."
type: docs
weight: 190
url: /es/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> Representa una clase para convertir páginas de documentos pdf a texto. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> El objeto {@code TextDevice} se utiliza básicamente para extraer texto de una página pdf. </p>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextDevice](#TextDevice--) | Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode. |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> Obtiene la codificación del texto extraído. </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> Obtiene la codificación del texto extraído. </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> Obtiene las opciones de extracción de texto. </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> Convierte la página y guárdala como flujo de texto. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convierte la página y guárdala como flujo de texto. |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | Establece la codificación del texto extraído. |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> Establece la codificación del texto extraído. </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Establece las opciones de extracción de texto. </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode.

### TextDevice {#TextDevice-java.nio.charset.Charset-}
Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
Inicializa una nueva instancia de {@code TextDevice} con el modo de formato de texto Raw y la codificación de texto Unicode.

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> Obtiene la codificación del texto extraído. </p>

**Returns:**
Elemento Charset <hr> <pre> The example demonstrates how to represent extracted text in UTF-8 encoding. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> Obtiene la codificación del texto extraído. </p>

**Returns:**
Elemento TextEncodingInternal <hr> <pre> The example demonstrates how to represent extracted text in UTF-8 encoding. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Obtiene las opciones de extracción de texto. </p>

**Returns:**
Elemento TextExtractionOptions <hr> <pre> El ejemplo muestra cómo extraer texto en orden bruto. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> Convierte la página y guárdala como flujo de texto. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Convierte la página y guárdala como flujo de texto.

### setEncoding {#setEncoding-java.nio.charset.Charset-}
Establece la codificación del texto extraído.

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> Establece la codificación del texto extraído. </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Establece las opciones de extracción de texto. </p>
