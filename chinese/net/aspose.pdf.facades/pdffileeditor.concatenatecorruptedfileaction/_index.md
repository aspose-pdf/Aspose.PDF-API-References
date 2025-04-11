---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction 枚举。当在连接过程中遇到损坏的文件时执行的操作
type: docs
weight: 4470
url: /zh/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction 枚举

当在连接过程中遇到损坏的文件时执行的操作。

```csharp
public enum ConcatenateCorruptedFileAction
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| StopWithError | `0` | 如果遇到损坏的文件，则停止连接过程并返回错误。 |
| ConcatenateIgnoringCorrupted | `1` | 如果遇到损坏的文件，则不停止连接并且不处理损坏的文件。损坏文件的列表可以在 Failures 属性中访问。 |
| ConcatenateIgnoringCorruptedObjects | `2` | 当在源文档中遇到损坏的对象时，处理将不会停止，仅忽略损坏的对象。 |

### 另请参阅

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)