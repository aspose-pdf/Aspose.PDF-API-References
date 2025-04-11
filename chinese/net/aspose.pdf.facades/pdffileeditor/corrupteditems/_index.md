---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 属性。执行连接时遇到的问题数组。对于传递给 Concatenate 函数的每个损坏文档，都会创建一个新的 CorruptedItem 条目。仅当 CorruptedFileAction 为 ConcatenateIgnoringCorrupted 时，可以使用此属性。
type: docs
weight: 90
url: /zh/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems 属性

执行连接时遇到的问题数组。对于传递给 Concatenate() 函数的每个损坏文档，都会创建一个新的 CorruptedItem 条目。仅当 CorruptedFileAction 为 ConcatenateIgnoringCorrupted 时，可以使用此属性。

```csharp
//concatenate documents and show information about corrupted documents
PdfFileEditor pfe = new PdfFileEditor();
pfe.CorruptedFileAction = PdfFileEditor.ConcatenateCorruptedFileActions.ConcatenateIgnoringCorrupted;
if (pfe.CorruptedItems.Length >0)
{
  foreach(PdfFileEditor.CorruptedItem item in pfe.CorruptedItems)
  {
     Console.WriteLine(item.Index + " reason: " + item.Exception);
  }
}
```

```csharp
public CorruptedItem[] CorruptedItems { get; }
```

### 另请参阅

* 类 [CorruptedItem](../../pdffileeditor.corrupteditem/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)