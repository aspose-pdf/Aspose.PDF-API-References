---
title: TiffDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: TiffDevice 方法。将某些文档页面转换为 tiff 并将其保存在输出流中
type: docs
weight: 90
url: /zh/net/aspose.pdf.devices/tiffdevice/process/
---
## Process(Document, int, int, Stream) {#process}

将某些文档页面转换为 tiff 并将其保存在输出流中。

```csharp
public override void Process(Document document, int fromPage, int toPage, Stream output)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | Document | 要转换的文档。 |
| fromPage | Int32 | 定义转换开始的页面编号。 |
| toPage | Int32 | 定义转换结束的页面编号。 |
| output | Stream | 包含 tiff 图像的输出流。 |

### 另见

* class [Document](../../../aspose.pdf/document/)
* class [TiffDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Page, Stream) {#process_4}

```csharp
public override void Process(Page page, Stream output)
```

### 另见

* class [Page](../../../aspose.pdf/page/)
* class [TiffDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)