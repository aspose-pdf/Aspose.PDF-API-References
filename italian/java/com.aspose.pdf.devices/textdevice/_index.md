---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta la classe per convertire le pagine di un documento pdf in testo. </p> <hr> <pre> L'esempio dimostra come estrarre il testo nella prima pagina del documento PDF. Document doc = new."
type: docs
weight: 190
url: /it/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> Rappresenta una classe per convertire le pagine del documento pdf in testo. </p> <hr> <pre> L'esempio dimostra come estrarre il testo dalla prima pagina del documento PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> L'oggetto {@code TextDevice} è fondamentalmente usato per estrarre il testo dalla pagina pdf. </p>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextDevice](#TextDevice--) | Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode. |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> Ottiene la codifica del testo estratto. </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> Ottiene la codifica del testo estratto. </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> Ottiene le opzioni di estrazione del testo. </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> Converti la pagina e salvala come flusso di testo. </p> <hr> <pre> L'esempio dimostra come estrarre il testo nella prima pagina del documento PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converti la pagina e salvala come flusso di testo. |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | Imposta la codifica del testo estratto. |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> Imposta la codifica del testo estratto. </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Imposta le opzioni di estrazione del testo. </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode.

### TextDevice {#TextDevice-java.nio.charset.Charset-}
Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
Inizializza una nuova istanza di {@code TextDevice} con la modalità di formattazione del testo Raw e la codifica Unicode.

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> Ottiene la codifica del testo estratto. </p>

**Returns:**
Elemento Charset <hr> <pre> L'esempio dimostra come rappresentare il testo estratto con codifica UTF-8. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> Ottiene la codifica del testo estratto. </p>

**Returns:**
Elemento TextEncodingInternal <hr> <pre> L'esempio dimostra come rappresentare il testo estratto con codifica UTF-8. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Ottiene le opzioni di estrazione del testo. </p>

**Returns:**
Elemento TextExtractionOptions <hr> <pre> L'esempio dimostra come estrarre il testo in ordine grezzo. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> Converti la pagina e salvala come flusso di testo. </p> <hr> <pre> L'esempio dimostra come estrarre il testo nella prima pagina del documento PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converti la pagina e salvala come flusso di testo.

### setEncoding {#setEncoding-java.nio.charset.Charset-}
Imposta la codifica del testo estratto.

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> Imposta la codifica del testo estratto. </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Imposta le opzioni di estrazione del testo. </p>
