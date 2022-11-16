---
title: TextDevice
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示将 pdf 文档页面转换为文本的类。
type: docs
weight: 26
url: /zh/java/com.aspose.pdf.devices/textdevice/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice)
```
public final class TextDevice extends PageDevice
```

表示将 pdf 文档页面转换为文本的类。

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
	       try 
	       {
	           // create text device
	           TextDevice device = new TextDevice();
	           // convert the page and save text to the stream
	           device.process(doc.getPages().get_Item(1), ms);
	           // use the extracted text	           
	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
	           
		    ms.close();
		} catch (IOException e) {
		    e.printStackTrace();
		}
```

--------------------

TextDevice 对象主要用于从 pdf 页面中提取文本。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextDevice(TextExtractionOptions extractionOptions)](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | 使用文本提取选项初始化 TextDevice 的新实例。 |
| [TextDevice()](#TextDevice--) | 使用 Raw 文本格式化模式和 Unicode 文本编码初始化 TextDevice 的新实例。 |
| [TextDevice(TextEncodingInternal encoding)](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | 为指定的编码初始化 TextDevice 的新实例。 |
| [TextDevice(Charset encoding)](#TextDevice-java.nio.charset.Charset-) | 为指定的编码初始化 TextDevice 的新实例。 |
| [TextDevice(TextExtractionOptions extractionOptions, TextEncodingInternal encoding)](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | 使用文本提取选项为指定编码初始化 TextDevice 的新实例。 |
| [TextDevice(TextExtractionOptions extractionOptions, Charset encoding)](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | 使用文本提取选项为指定编码初始化 TextDevice 的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | 获取提取文本的编码。 |
| [getEncodingInternal()](#getEncodingInternal--) | 获取提取文本的编码。 |
| [getExtractionOptions()](#getExtractionOptions--) | 获取文本提取选项。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(Page page, System.Drawing.Graphics gr)](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | 在图形上呈现页面 |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | 转换页面并将其保存为文本流。 |
| [process(Page page, String outputFileName)](#process-com.aspose.pdf.Page-java.lang.String-) | 在给定页面上执行一些操作并将结果保存到文件中。 |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 转换页面并将其保存为文本流。 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 设置提取文本的编码。 |
| [setEncodingInternal(TextEncodingInternal value)](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | 设置提取文本的编码。 |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | 设置文本提取选项。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextDevice(TextExtractionOptions extractionOptions) {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
```
public TextDevice(TextExtractionOptions extractionOptions)
```


使用文本提取选项初始化 TextDevice 的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | 文本提取选项。 |

### TextDevice() {#TextDevice--}
```
public TextDevice()
```


使用 Raw 文本格式化模式和 Unicode 文本编码初始化 TextDevice 的新实例。

### TextDevice(TextEncodingInternal encoding) {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
```
public TextDevice(TextEncodingInternal encoding)
```


为指定的编码初始化 TextDevice 的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| encoding | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | 提取文本的编码 |

### TextDevice(Charset encoding) {#TextDevice-java.nio.charset.Charset-}
```
public TextDevice(Charset encoding)
```


为指定的编码初始化 TextDevice 的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| encoding | java.nio.charset.Charset | 提取文本的编码 |

### TextDevice(TextExtractionOptions extractionOptions, TextEncodingInternal encoding) {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
```
public TextDevice(TextExtractionOptions extractionOptions, TextEncodingInternal encoding)
```


使用文本提取选项为指定编码初始化 TextDevice 的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | 文本提取选项。 |
| encoding | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | 提取文本的编码。 |

### TextDevice(TextExtractionOptions extractionOptions, Charset encoding) {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
```
public TextDevice(TextExtractionOptions extractionOptions, Charset encoding)
```


使用文本提取选项为指定编码初始化 TextDevice 的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | 文本提取选项。 |
| encoding | java.nio.charset.Charset | 提取文本的编码。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


获取提取文本的编码。

**退货：**
java.nio.charset.Charset - 字符集元素

--------------------

```
The example demonstrates how to represent extracted text in UTF-8 encoding.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // create text device
	       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
	       // convert the page and save text to the stream
	       device.process(doc.getPages().get_Item(1), outFile);
```
### getEncodingInternal() {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```


获取提取文本的编码。

**退货：**
[TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) TextEncoding内部元素

--------------------

```
The example demonstrates how to represent extracted text in UTF-8 encoding.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // create text device
	       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
	       // convert the page and save text to the stream
	       device.process(doc.getPages().get_Item(1), outFile);
```
### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


获取文本提取选项。

**退货：**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) TextExtractionOptions 元素

--------------------

```
The example demonstrates how to extracted text in raw order.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // create text device
	       TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));
	       // convert the page and save text to the stream
	       device.process(doc.getPages().get_Item(1), outFile);
```
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### process(Page page, System.Drawing.Graphics gr) {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
```
public void process(Page page, System.Drawing.Graphics gr)
```


在图形上呈现页面

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 页面对象 |
| gr | com.aspose.ms.System.Drawing.Graphics | 内部对象 |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```


转换页面并将其保存为文本流。

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
	       
	           // create text device
	           TextDevice device = new TextDevice();
	           // convert the page and save text to the stream
	           device.process(doc.getPages().get_Item(1), ms);
	           // use the extracted text
	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
	           ms.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要转换的页面。 |
| output | java.io.OutputStream | 结果流。 |

### process(Page page, String outputFileName) {#process-com.aspose.pdf.Page-java.lang.String-}
```
public void process(Page page, String outputFileName)
```


在给定页面上执行一些操作并将结果保存到文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要处理的页面。 |
| outputFileName | java.lang.String | 该文件包含处理结果。 |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


转换页面并将其保存为文本流。

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       ByteArrayOutputStream ms = new ByteArrayOutputStream();
	       
	           // create text device
	           TextDevice device = new TextDevice();
	           // convert the page and save text to the stream
	           device.process(doc.getPages().get_Item(1), ms);
	           // use the extracted text
	           extractedText = Encoding.getUnicode().getString(ms.toByteArray());
	           ms.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要转换的页面。 |
| output | com.aspose.ms.System.IO.Stream | 结果流。 |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


设置提取文本的编码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.nio.charset.Charset | 字符集元素

--------------------

```
The example demonstrates how to represent extracted text in UTF-8 encoding.
 
		       Document doc = new Document(inFile);
		       String extractedText;
		       // create text device
		       TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8"));
		       // convert the page and save text to the stream
		       device.process(doc.getPages().get_Item(1), outFile);
``` |

### setEncodingInternal(TextEncodingInternal value) {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
```
public void setEncodingInternal(TextEncodingInternal 值)
```


Sets encoding of extracted text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | TextEncodingInternal element

--------------------

```
该示例演示了如何以 UTF-8 编码表示提取的文本。
 
		       Document doc = new Document(inFile);
		       String extractedText;
		       // create text device
		       TextDevice device = new TextDevice(TextEncodingInternal.getUTF8());
		       // convert the page and save text to the stream
		       device.process(doc.getPages().get_Item(1), outFile);
``` |

### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions（TextExtractionOptions 值）
```


Sets text extraction options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | TextExtractionOptions element

--------------------

```
该示例演示了如何以原始顺序提取文本。
 
	       Document doc = new Document(inFile);
	       String extractedText;
	       // create text device
	       TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));
	       // convert the page and save text to the stream
	       device.process(doc.getPages().get_Item(1), outFile);
``` |

### toString() {#toString--}
```
公共字符串 toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
公共最终无效等待（）
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
公共最终无效等待（长 arg0，int arg1）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
