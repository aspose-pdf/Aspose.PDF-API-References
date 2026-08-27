---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa a classe para converter páginas de documentos pdf em texto. </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. Document doc = new."
type: docs
weight: 190
url: /pt/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> Representa uma classe para converter páginas de documentos pdf em texto. </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // cria dispositivo de texto TextDevice device = new TextDevice(); // converte a página e salva o texto no fluxo device.process(doc.getPages().get_Item(1), ms); // usa o texto extraído extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> O objeto {@code TextDevice} é basicamente usado para extrair texto da página pdf. </p>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextDevice](#TextDevice--) | Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode. |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> Obtém a codificação do texto extraído. </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> Obtém a codificação do texto extraído. </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> Obtém as opções de extração de texto. </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> Converte a página e a salva como fluxo de texto. </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converte a página e a salva como fluxo de texto. |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | Define a codificação do texto extraído. |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> Define a codificação do texto extraído. </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Define as opções de extração de texto. </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode.

### TextDevice {#TextDevice-java.nio.charset.Charset-}
Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
Inicializa uma nova instância do {@code TextDevice} com o modo de formatação de texto Raw e codificação de texto Unicode.

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> Obtém a codificação do texto extraído. </p>

**Returns:**
Charset element <hr> <pre> O exemplo demonstra como representar o texto extraído com codificação UTF-8. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> Obtém a codificação do texto extraído. </p>

**Returns:**
TextEncodingInternal element <hr> <pre> O exemplo demonstra como representar o texto extraído com codificação UTF-8. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Obtém as opções de extração de texto. </p>

**Returns:**
TextExtractionOptions element <hr> <pre> O exemplo demonstra como extrair texto em ordem bruta. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> Converte a página e a salva como fluxo de texto. </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converte a página e a salva como fluxo de texto.

### setEncoding {#setEncoding-java.nio.charset.Charset-}
Define a codificação do texto extraído.

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> Define a codificação do texto extraído. </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Define as opções de extração de texto. </p>
