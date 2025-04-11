---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfFileEditor. Массив обнаруженных проблем при выполнении конкатенации. Для каждого поврежденного документа, переданного в функцию Concatenate, создается новая запись CorruptedItem. Это свойство может использоваться только тогда, когда CorruptedFileAction равно ConcatenateIgnoringCorrupted.
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## Свойство PdfFileEditor.CorruptedItems

Массив обнаруженных проблем при выполнении конкатенации. Для каждого поврежденного документа, переданного в функцию Concatenate(), создается новая запись CorruptedItem. Это свойство может использоваться только тогда, когда CorruptedFileAction равно ConcatenateIgnoringCorrupted.

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

### См. также

* класс [CorruptedItem](../../pdffileeditor.corrupteditem/)
* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)