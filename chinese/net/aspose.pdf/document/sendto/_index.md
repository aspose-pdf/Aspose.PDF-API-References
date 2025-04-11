---
title: Document.SendTo
second_title: Aspose.PDF for .NET API Reference
description: Document 方法。将整个文档发送到文档设备进行处理
type: docs
weight: 860
url: /zh/net/aspose.pdf/document/sendto/
---
## SendTo(DocumentDevice, Stream) {#sendto_2}

将整个文档发送到文档设备进行处理。

```csharp
public void SendTo(DocumentDevice device, Stream output)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| device | DocumentDevice | 用于处理文档的文档设备。 |
| output | Stream | 输出流包含使用给定设备处理文档的结果。 |

### 另见

* class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SendTo(DocumentDevice, int, int, Stream) {#sendto}

将文档的特定页面发送到文档设备进行处理。

```csharp
public void SendTo(DocumentDevice device, int fromPage, int toPage, Stream output)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| device | DocumentDevice | 用于处理文档的文档设备。 |
| fromPage | Int32 | 处理的第一页。 |
| toPage | Int32 | 处理的最后一页。 |
| output | Stream | 输出流包含使用给定设备处理文档页面的结果。 |

### 另见

* class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SendTo(DocumentDevice, string) {#sendto_3}

将整个文档发送到文档设备进行处理。

```csharp
public void SendTo(DocumentDevice device, string outputFileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| device | DocumentDevice | 用于处理文档的文档设备。 |
| outputFileName | String | 处理结果的输出文件名。 |

### 另见

* class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SendTo(DocumentDevice, int, int, string) {#sendto_1}

将整个文档发送到文档设备进行处理。

```csharp
public void SendTo(DocumentDevice device, int fromPage, int toPage, string outputFileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| device | DocumentDevice | 用于处理文档的文档设备。 |
| fromPage | Int32 | 处理的第一页。 |
| toPage | Int32 | 处理的最后一页。 |
| outputFileName | String | 处理结果的输出文件名。 |

### 另见

* class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)