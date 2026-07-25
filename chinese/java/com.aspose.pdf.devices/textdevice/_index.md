---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示用于将 pdf 文档页面转换为文本的类。 </p> <hr> <pre> 示例演示如何提取第一个 PDF 文档页面的文本。 Document doc = new."
type: docs
weight: 190
url: /zh/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> 表示用于将 pdf 文档页面转换为文本的类。 </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> {@code TextDevice} 对象主要用于从 pdf 页面提取文本。 </p>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextDevice](#TextDevice--) | 使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。 |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | 使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。 |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | 使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。 |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | 使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。 |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | 使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。 |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | 使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> 获取提取文本的编码。 </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> 获取提取文本的编码。 </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> 获取文本提取选项。 </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> 将页面转换并保存为文本流。 </p> <hr> <pre> 示例演示如何提取第一个 PDF 文档页面的文本。 Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 将页面转换并保存为文本流。 |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | 设置提取文本的编码。 |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> 设置提取文本的编码。 </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> 设置文本提取选项。 </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。

### TextDevice {#TextDevice-java.nio.charset.Charset-}
使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
使用原始文本格式模式和 Unicode 文本编码初始化 {@code TextDevice} 的新实例。

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> 获取提取文本的编码。 </p>

**Returns:**
Charset element <hr> <pre> 示例演示如何以 UTF-8 编码表示提取的文本。 Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> 获取提取文本的编码。 </p>

**Returns:**
TextEncodingInternal element <hr> <pre> 示例演示如何以 UTF-8 编码表示提取的文本。 Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> 获取文本提取选项。 </p>

**Returns:**
TextExtractionOptions element <hr> <pre> 示例演示如何以原始顺序提取文本。 Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> 将页面转换并保存为文本流。 </p> <hr> <pre> 示例演示如何提取第一个 PDF 文档页面的文本。 Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
将页面转换并保存为文本流。

### setEncoding {#setEncoding-java.nio.charset.Charset-}
设置提取文本的编码。

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> 设置提取文本的编码。 </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> 设置文本提取选项。 </p>
