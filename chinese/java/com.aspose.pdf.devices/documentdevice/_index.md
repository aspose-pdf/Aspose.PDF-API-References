---
title: "DocumentDevice"
linktitle: "DocumentDevice"
second_title: "Aspose.PDF for Java API 参考"
description: "用于处理整个 pdf 文档的所有设备的抽象类。"
type: docs
weight: 60
url: /zh/java/com.aspose.pdf.devices/documentdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice

```
public abstract class DocumentDevice extends PageDevice
```

用于处理整个 pdf 文档的所有设备的抽象类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DocumentDevice](#DocumentDevice--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | 每个设备代表对文档的某种操作，例如我们可以将 PDF 文档转换为其他格式。 |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | 处理文档的特定页面并将结果保存到文件。 |
| [process](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | 处理整个文档并将结果保存到流中。 |
| [process](#process-com.aspose.pdf.IDocument-java.lang.String-) | 处理整个文档并将结果保存到文件。 |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | 每个设备代表对文档的某种操作，例如。 |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | 处理整个文档并将结果保存到流中。 |

### DocumentDevice {#DocumentDevice--}
```
public DocumentDevice()
```



### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
每个设备代表对文档的某种操作，例如我们可以将 PDF 文档转换为其他格式。

### process {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
处理文档的特定页面并将结果保存到文件。

### process {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
处理整个文档并将结果保存到流中。

### process {#process-com.aspose.pdf.IDocument-java.lang.String-}
处理整个文档并将结果保存到文件。

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
每个设备代表对文档的某种操作，例如。

### processInternal {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
处理整个文档并将结果保存到流中。
