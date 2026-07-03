---
title: TextDevice
second_title: Aspose.PDF for Java API Reference
description: <p> Represents class for converting pdf document pages into text. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new.
type: docs
weight: 190
url: /java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> Represents class for converting pdf document pages into text. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> The {@code TextDevice} object is basically used to extract text from pdf page. </p>

## Constructors

| Constructor | Description |
| --- | --- |
| [TextDevice](#TextDevice--) | Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding. |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding. |

## Methods

| Method | Description |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> Gets encoding of extracted text. </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> Gets encoding of extracted text. </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> Gets text extraction options. </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> Convert page and save it as text stream. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convert page and save it as text stream. |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | Sets encoding of extracted text. |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> Sets encoding of extracted text. </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Sets text extraction options. </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding.

### TextDevice {#TextDevice-java.nio.charset.Charset-}
Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding.

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
Initializes a new instance of the {@code TextDevice} with the Raw text formatting mode and Unicode text encoding.

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> Gets encoding of extracted text. </p>

**Returns:**
Charset element <hr> <pre> The example demonstrates how to represent extracted text in UTF-8 encoding. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> Gets encoding of extracted text. </p>

**Returns:**
TextEncodingInternal element <hr> <pre> The example demonstrates how to represent extracted text in UTF-8 encoding. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Gets text extraction options. </p>

**Returns:**
TextExtractionOptions element <hr> <pre> The example demonstrates how to extracted text in raw order. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> Convert page and save it as text stream. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Convert page and save it as text stream.

### setEncoding {#setEncoding-java.nio.charset.Charset-}
Sets encoding of extracted text.

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> Sets encoding of extracted text. </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Sets text extraction options. </p>
