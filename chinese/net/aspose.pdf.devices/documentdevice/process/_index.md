---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: DocumentDevice 方法。每个设备代表对文档的某种操作，例如，我们可以将 PDF 文档转换为另一种格式
type: docs
weight: 10
url: /zh/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

每个设备代表对文档的某种操作，例如，我们可以将 PDF 文档转换为另一种格式。

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | Document | 要处理的文档。 |
| fromPage | Int32 | 定义开始处理的页面。 |
| toPage | Int32 | 定义要处理的最后一页。 |
| output | Stream | 定义存储处理结果的流。 |

### 另见

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

处理整个文档并将结果保存到流中。

```csharp
public void Process(Document document, Stream output)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | Document | 要处理的文档。 |
| output | Stream | 定义存储处理结果的流。 |

### 另见

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

处理整个文档并将结果保存到文件中。

```csharp
public void Process(Document document, string outputFileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | Document | 要处理的文档。 |
| outputFileName | String | 定义存储处理结果的文件。 |

### 另见

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

处理文档的特定页面并将结果保存到文件中。

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | Document | 要处理的文档。 |
| fromPage | Int32 | 开始处理的第一页。 |
| toPage | Int32 | 处理的最后一页。 |
| outputFileName | String | 定义存储处理结果的文件。 |

### 另见

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)