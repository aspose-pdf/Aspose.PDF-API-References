---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar en klass för att konvertera pdf-dokumentssidor till text. </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentssidan. Document doc = new."
type: docs
weight: 190
url: /sv/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> Representerar en klass för att konvertera PDF-dokumentets sidor till text. </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentets sida. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // skapa textenhet TextDevice device = new TextDevice(); // konvertera sidan och spara text till strömmen device.process(doc.getPages().get_Item(1), ms); // använd den extraherade texten extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> Objektet {@code TextDevice} används i princip för att extrahera text från en PDF-sida. </p>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextDevice](#TextDevice--) | Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning. |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> Hämtar kodning för extraherad text. </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> Hämtar kodning för extraherad text. </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> Hämtar alternativ för textextraktion. </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> Konvertera sidan och spara den som textström. </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentssidan. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Konvertera sidan och spara den som textström. |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | Ställer in kodning för extraherad text. |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> Ställer in kodning för extraherad text. </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Ställer in alternativ för textextraktion. </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning.

### TextDevice {#TextDevice-java.nio.charset.Charset-}
Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning.

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
Initierar en ny instans av {@code TextDevice} med rå textformateringsläge och Unicode-textkodning.

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> Hämtar kodning för extraherad text. </p>

**Returns:**
Charset-element <hr> <pre> Exemplet visar hur man representerar extraherad text i UTF-8-kodning. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> Hämtar kodning för extraherad text. </p>

**Returns:**
TextEncodingInternal-element <hr> <pre> Exemplet visar hur man representerar extraherad text i UTF-8-kodning. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Hämtar alternativ för textextraktion. </p>

**Returns:**
TextExtractionOptions-element <hr> <pre> Exemplet visar hur man extraherar text i rå ordning. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> Konvertera sidan och spara den som textström. </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentssidan. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Konvertera sidan och spara den som textström.

### setEncoding {#setEncoding-java.nio.charset.Charset-}
Ställer in kodning för extraherad text.

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> Ställer in kodning för extraherad text. </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Ställer in alternativ för textextraktion. </p>
