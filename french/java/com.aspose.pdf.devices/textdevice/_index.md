---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente la classe permettant de convertir les pages d'un document pdf en texte. </p> <hr> <pre> L'exemple montre comment extraire le texte de la première page du document PDF. Document doc = new."
type: docs
weight: 190
url: /fr/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> Représente une classe permettant de convertir les pages de documents PDF en texte. </p> <hr> <pre> L'exemple montre comment extraire le texte de la première page du document PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> L'objet {@code TextDevice} est essentiellement utilisé pour extraire le texte d'une page PDF. </p>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextDevice](#TextDevice--) | Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode. |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> Obtient l'encodage du texte extrait. </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> Obtient l'encodage du texte extrait. </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> Obtient les options d'extraction de texte. </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> Convertit la page et l'enregistre en flux de texte. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convertit la page et l'enregistre en flux de texte. |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | Définit l'encodage du texte extrait. |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> Définit l'encodage du texte extrait. </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Définit les options d'extraction de texte. </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode.

### TextDevice {#TextDevice-java.nio.charset.Charset-}
Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
Initialise une nouvelle instance de {@code TextDevice} avec le mode de formatage de texte Raw et l'encodage de texte Unicode.

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> Obtient l'encodage du texte extrait. </p>

**Returns:**
Élément Charset <hr> <pre> The example demonstrates how to represent extracted text in UTF-8 encoding. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> Obtient l'encodage du texte extrait. </p>

**Returns:**
Élément TextEncodingInternal <hr> <pre> The example demonstrates how to represent extracted text in UTF-8 encoding. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Obtient les options d'extraction de texte. </p>

**Returns:**
Élément TextExtractionOptions <hr> <pre> The example demonstrates how to extracted text in raw order. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> Convertit la page et l'enregistre en flux de texte. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Convertit la page et l'enregistre en flux de texte.

### setEncoding {#setEncoding-java.nio.charset.Charset-}
Définit l'encodage du texte extrait.

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> Définit l'encodage du texte extrait. </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Définit les options d'extraction de texte. </p>
