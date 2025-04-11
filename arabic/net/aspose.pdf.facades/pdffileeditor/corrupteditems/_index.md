---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfFileEditor. مصفوفة من المشاكل التي تم مواجهتها عند تنفيذ الدمج. لكل مستند تالف تم تمريره إلى دالة Concatenate يتم إنشاء إدخال جديد من نوع CorruptedItem. يمكن استخدام هذه الخاصية فقط عندما تكون CorruptedFileAction هي ConcatenateIgnoringCorrupted
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## خاصية PdfFileEditor.CorruptedItems

مصفوفة من المشاكل التي تم مواجهتها عند تنفيذ الدمج. لكل مستند تالف تم تمريره إلى دالة Concatenate() يتم إنشاء إدخال جديد من نوع CorruptedItem. يمكن استخدام هذه الخاصية فقط عندما تكون CorruptedFileAction هي ConcatenateIgnoringCorrupted.

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

### انظر أيضًا

* class [CorruptedItem](../../pdffileeditor.corrupteditem/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)