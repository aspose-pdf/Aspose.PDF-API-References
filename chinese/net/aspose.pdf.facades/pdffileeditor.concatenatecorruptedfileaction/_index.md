---
title: PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API 参考
description: 在连接过程中遇到损坏的文件时执行的操作
type: docs
weight: 2480
url: /zh/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

在连接过程中遇到损坏的文件时执行的操作。

```csharp
public enum ConcatenateCorruptedFileAction
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| StopWithError | `0` | 如果遇到损坏的文件，则停止连接过程并返回错误。 |
| ConcatenateIgnoringCorrupted | `1` | 如果遇到损坏的文件，则不要停止连接，也不要处理损坏的文件。 可在故障属性中访问损坏的文件列表。 |
| ConcatenateIgnoringCorruptedObjects | `2` | 当源文档中遇到损坏的对象时，进程不会停止并且仅忽略损坏的对象。 |

### 也可以看看

* class [PdfFileEditor](../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->