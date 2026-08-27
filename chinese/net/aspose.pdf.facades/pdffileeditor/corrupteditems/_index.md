---
title: "PdfFileEditor.CorruptedItems"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 属性。连接操作执行时遇到的问题数组。对于传递给 Concatenate 函数的每个损坏文档，都会创建一个新的 CorruptedItem 条目。仅当 CorruptedFileAction 为 ConcatenateIgnoringCorrupted 时才可以使用此属性。"
type: docs
weight: 90
url: /zh/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems property

在执行合并时遇到的问题数组。对于传递给 Concatenate() 函数的每个损坏文档，都会创建一个新的 CorruptedItem 条目。仅当 CorruptedFileAction 为 ConcatenateIgnoringCorrupted 时才能使用此属性。

```csharp
//连接文档并显示有关损坏文档的信息
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

### 另请参见

* class [CorruptedItem](../../pdffileeditor.corrupteditem/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


