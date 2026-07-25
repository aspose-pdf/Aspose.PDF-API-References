---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل الفئة لتحويل صفحات مستند pdf إلى نص. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. Document doc = new."
type: docs
weight: 190
url: /ar/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> تمثل فئة لتحويل صفحات مستند PDF إلى نص. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // إنشاء جهاز النص TextDevice device = new TextDevice(); // تحويل الصفحة وحفظ النص إلى الدفق device.process(doc.getPages().get_Item(1), ms); // استخدام النص المستخرج extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> كائن {@code TextDevice} يُستخدم أساسًا لاستخراج النص من صفحة PDF. </p>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextDevice](#TextDevice--) | يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود. |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> يحصل على ترميز النص المستخرج. </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> يحصل على ترميز النص المستخرج. </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> يحصل على خيارات استخراج النص. </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> تحويل الصفحة وحفظها كتيار نصي. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | تحويل الصفحة وحفظها كتيار نصي. |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | يضبط ترميز النص المستخرج. |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> يضبط ترميز النص المستخرج. </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> يضبط خيارات استخراج النص. </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود.

### TextDevice {#TextDevice-java.nio.charset.Charset-}
يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود.

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
يُنشئ مثيلاً جديدًا من {@code TextDevice} باستخدام وضع تنسيق النص الخام وترميز النص يونيكود.

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> يحصل على ترميز النص المستخرج. </p>

**Returns:**
عنصر Charset <hr> <pre> يوضح المثال كيفية تمثيل النص المستخرج بترميز UTF-8. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> يحصل على ترميز النص المستخرج. </p>

**Returns:**
عنصر TextEncodingInternal <hr> <pre> يوضح المثال كيفية تمثيل النص المستخرج بترميز UTF-8. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> يحصل على خيارات استخراج النص. </p>

**Returns:**
عنصر TextExtractionOptions <hr> <pre> يوضح المثال كيفية استخراج النص بترتيب خام. Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> تحويل الصفحة وحفظها كتيار نصي. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
تحويل الصفحة وحفظها كتيار نصي.

### setEncoding {#setEncoding-java.nio.charset.Charset-}
يضبط ترميز النص المستخرج.

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> يضبط ترميز النص المستخرج. </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> يضبط خيارات استخراج النص. </p>
