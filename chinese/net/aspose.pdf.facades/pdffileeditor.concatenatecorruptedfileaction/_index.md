---
title: "枚举 PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction 枚举。当在合并过程中遇到损坏的文件时执行的操作。"
type: docs
weight: 4590
url: /zh/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

在合并过程中遇到损坏的文件时执行的操作。

```csharp
public enum ConcatenateCorruptedFileAction
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| StopWithError | `0` | 如果遇到损坏的文件，则停止合并过程并返回错误。 |
| ConcatenateIgnoringCorrupted | `1` | 如果遇到损坏的文件，则不停止合并，也不处理损坏的文件。损坏文件的列表可通过 Failures 属性访问。 |
| ConcatenateIgnoringCorruptedObjects | `2` | 当在源 Document 中遇到损坏的对象时，过程不会停止，且仅忽略该损坏对象。 |

### 另请参见

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


