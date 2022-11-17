---
title: DocumentDevice
second_title: 用于 Java API 参考的 Aspose.PDF
description: 用于处理整个 pdf 文档的所有设备的抽象类。
type: docs
weight: 14
url: /zh/java/com.aspose.pdf.devices/documentdevice/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device)
```
public abstract class DocumentDevice extends Device
```

用于处理整个 pdf 文档的所有设备的抽象类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DocumentDevice()](#DocumentDevice--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold)](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | 对输入流进行 Bradley 二值化。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(IDocument document, int fromPage, int toPage, OutputStream output)](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | 每个设备代表对文档的一些操作，例如我们可以将pdf文档转换成另一种格式。 |
| [process(IDocument document, int fromPage, int toPage, String outputFileName)](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | 处理文档的某些页面并将结果保存到文件中。 |
| [process(IDocument document, OutputStream output)](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | 处理整个文档并将结果保存到流中。 |
| [process(IDocument document, String outputFileName)](#process-com.aspose.pdf.IDocument-java.lang.String-) | 处理整个文档并将结果保存到文件中。 |
| [processInternal(IDocument document, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | 处理整个文档并将结果保存到流中。 |
| [processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | 每个设备代表对文档的一些操作，例如我们可以将pdf文档转换成另一种格式。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentDevice() {#DocumentDevice--}
```
public DocumentDevice()
```


### binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold) {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
```
public void binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold)
```


对输入流进行 Bradley 二值化。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputImageStream | java.io.InputStream | 输入图像流。 |
| outputImageStream | java.io.OutputStream | 输出图像流。 |
| threshold | double | 阈值介于 0.0 和 1.0 之间。 |

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




### process(IDocument document, int fromPage, int toPage, OutputStream output) {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
```
public void process(IDocument document, int fromPage, int toPage, OutputStream output)
```


每个设备代表对文档的一些操作，例如我们可以将pdf文档转换成另一种格式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要处理的文档。 |
| fromPage | int | 定义开始处理的页面。 |
| toPage | int | 定义要处理的最后一页。 |
| output | java.io.OutputStream | 定义存储处理结果的流。 |

### process(IDocument document, int fromPage, int toPage, String outputFileName) {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
```
public void process(IDocument document, int fromPage, int toPage, String outputFileName)
```


处理文档的某些页面并将结果保存到文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要处理的文档。 |
| fromPage | int | 开始处理的第一页。 |
| toPage | int | 处理的最后一页。 |
| outputFileName | java.lang.String | 定义存储处理结果的文件。 |

### process(IDocument document, OutputStream output) {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public void process(IDocument document, OutputStream output)
```


处理整个文档并将结果保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要处理的文档。 |
| output | java.io.OutputStream | 定义存储处理结果的流。 |

### process(IDocument document, String outputFileName) {#process-com.aspose.pdf.IDocument-java.lang.String-}
```
public void process(IDocument document, String outputFileName)
```


处理整个文档并将结果保存到文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要处理的文档。 |
| outputFileName | java.lang.String | 定义存储处理结果的文件。 |

### processInternal(IDocument document, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(IDocument document, System.IO.Stream output)
```


处理整个文档并将结果保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要处理的文档。 |
| output | com.aspose.ms.System.IO.Stream | 定义存储处理结果的流。 |

### processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
```
public abstract void processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)
```


每个设备代表对文档的一些操作，例如我们可以将pdf文档转换成另一种格式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要处理的文档。 |
| fromPage | int | 定义开始处理的页面。 |
| toPage | int | 定义要处理的最后一页。 |
| output | com.aspose.ms.System.IO.Stream | 定义存储处理结果的流。 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
