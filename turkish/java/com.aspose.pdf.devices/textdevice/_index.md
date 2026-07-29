---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> pdf belge sayfalarını metne dönüştürmek için sınıfı temsil eder. </p> <hr> <pre> Örnek, ilk PDF belge sayfasından metin nasıl çıkarılacağını gösterir. Document doc = new."
type: docs
weight: 190
url: /tr/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> Pdf belge sayfalarını metne dönüştürmek için sınıfı temsil eder. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> The {@code TextDevice} object is basically used to extract text from pdf page. </p>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextDevice](#TextDevice--) | Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır. |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> Çıkarılan metnin kodlamasını alır. </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> Çıkarılan metnin kodlamasını alır. </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> Metin çıkarma seçeneklerini alır. </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> Sayfayı dönüştür ve metin akışı olarak kaydet. </p> <hr> <pre> Örnek, ilk PDF belge sayfasındaki metnin nasıl çıkarılacağını gösterir. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Sayfayı dönüştür ve metin akışı olarak kaydet. |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | Çıkarılan metnin kodlamasını ayarlar. |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> Çıkarılan metnin kodlamasını ayarlar. </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Metin çıkarma seçeneklerini ayarlar. </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır.

### TextDevice {#TextDevice-java.nio.charset.Charset-}
Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır.

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
Raw metin biçimlendirme modu ve Unicode metin kodlamasıyla {@code TextDevice} sınıfının yeni bir örneğini başlatır.

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> Çıkarılan metnin kodlamasını alır. </p>

**Returns:**
Charset öğesi <hr> <pre> Örnek, çıkarılan metnin UTF-8 kodlamasıyla nasıl temsil edileceğini gösterir. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> Çıkarılan metnin kodlamasını alır. </p>

**Returns:**
TextEncodingInternal öğesi <hr> <pre> Örnek, çıkarılan metnin UTF-8 kodlamasıyla nasıl temsil edileceğini gösterir. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Metin çıkarma seçeneklerini alır. </p>

**Returns:**
TextExtractionOptions öğesi <hr> <pre> Örnek, metnin ham sırayla nasıl çıkarılacağını gösterir. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> Sayfayı dönüştür ve metin akışı olarak kaydet. </p> <hr> <pre> Örnek, ilk PDF belge sayfasındaki metnin nasıl çıkarılacağını gösterir. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Sayfayı dönüştür ve metin akışı olarak kaydet.

### setEncoding {#setEncoding-java.nio.charset.Charset-}
Çıkarılan metnin kodlamasını ayarlar.

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> Çıkarılan metnin kodlamasını ayarlar. </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Metin çıkarma seçeneklerini ayarlar. </p>
