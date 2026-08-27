---
title: "PdfFileEditor.CorruptedItems"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfFileEditor. Массив обнаруженных проблем, возникших при выполнении объединения. Для каждого повреждённого документа, переданного в функцию Concatenate, создаётся новая запись CorruptedItem. Это свойство может использоваться только когда CorruptedFileAction имеет значение ConcatenateIgnoringCorrupted."
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems property

Массив возникших проблем при выполнении конкатенации. Для каждого повреждённого документа, переданного в функцию Concatenate(), создаётся новая запись CorruptedItem. Это свойство может использоваться только когда CorruptedFileAction имеет значение ConcatenateIgnoringCorrupted.

```csharp
//объединять документы и отображать информацию о повреждённых документах
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

* class [CorruptedItem](../../pdffileeditor.corrupteditem/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


