---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt eine Klasse zum Konvertieren von PDF-Dokumentseiten in Text dar. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten PDF-Dokumentseite extrahiert. Document doc = new."
type: docs
weight: 190
url: /de/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> Stellt eine Klasse zum Konvertieren von PDF-Dokumentseiten in Text dar. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten PDF-Dokumentseite extrahiert. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> Das {@code TextDevice}-Objekt wird im Wesentlichen verwendet, um Text aus einer PDF-Seite zu extrahieren. </p>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextDevice](#TextDevice--) | Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung. |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> Gibt die Kodierung des extrahierten Textes zurück. </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> Gibt die Kodierung des extrahierten Textes zurück. </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> Gibt die Optionen zur Textextraktion zurück. </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> Konvertiert die Seite und speichert sie als Text-Stream. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten PDF-Dokumentseite extrahiert. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Konvertiert die Seite und speichert sie als Text-Stream. |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | Setzt die Kodierung des extrahierten Textes. |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> Legt die Kodierung des extrahierten Textes fest. </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Legt die Optionen zur Textextraktion fest. </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung.

### TextDevice {#TextDevice-java.nio.charset.Charset-}
Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung.

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
Initialisiert eine neue Instanz des {@code TextDevice} mit dem Raw-Text-Formatierungsmodus und Unicode-Textkodierung.

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> Gibt die Kodierung des extrahierten Textes zurück. </p>

**Returns:**
Charset-Element <hr> <pre> Das Beispiel zeigt, wie extrahierter Text in UTF-8-Kodierung dargestellt wird. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> Gibt die Kodierung des extrahierten Textes zurück. </p>

**Returns:**
TextEncodingInternal-Element <hr> <pre> Das Beispiel zeigt, wie extrahierter Text in UTF-8-Kodierung dargestellt wird. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Gibt die Optionen zur Textextraktion zurück. </p>

**Returns:**
TextExtractionOptions-Element <hr> <pre> Das Beispiel zeigt, wie Text in roher Reihenfolge extrahiert wird. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> Konvertiert die Seite und speichert sie als Text-Stream. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten PDF-Dokumentseite extrahiert. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Konvertiert die Seite und speichert sie als Text-Stream.

### setEncoding {#setEncoding-java.nio.charset.Charset-}
Setzt die Kodierung des extrahierten Textes.

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> Legt die Kodierung des extrahierten Textes fest. </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Legt die Optionen zur Textextraktion fest. </p>
