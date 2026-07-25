---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Aspose.PDF for Java API 参考"
description: "在合并过程中遇到损坏文件时执行的操作。"
type: docs
weight: 420
url: /zh/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

在合并过程中遇到损坏文件时执行的操作。

## 字段

| 字段 | 描述 |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | 如果遇到损坏的文件，则不要停止合并，也不要处理该损坏的文件。损坏文件的列表可通过 Failures 属性访问。 |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | 当在源文档中遇到损坏的对象时，处理将不会停止，只会忽略该损坏的对象。 |
| [StopWithError](#StopWithError) | 如果遇到损坏的文件，则停止连接过程并返回错误。 |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

如果遇到损坏的文件，则不要停止合并，也不要处理该损坏的文件。损坏文件的列表可通过 Failures 属性访问。

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

当在源文档中遇到损坏的对象时，处理将不会停止，只会忽略该损坏的对象。

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

如果遇到损坏的文件，则停止连接过程并返回错误。
