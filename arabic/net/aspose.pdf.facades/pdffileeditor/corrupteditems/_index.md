---
title: "PdfFileEditor.CorruptedItems"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية PdfFileEditor. مصفوفة من المشكلات التي تم مواجهتها عند تنفيذ الجمع. لكل Document معطوب تم تمريره إلى دالة Concatenate يتم إنشاء إدخال CorruptedItem جديد. يمكن استخدام هذه الخاصية فقط عندما تكون قيمة CorruptedFileAction هي ConcatenateIgnoringCorrupted."
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems property

مصفوفة بالمشكلات التي تم مواجهتها عند تنفيذ الدمج. لكل مستند تالف تم تمريره إلى دالة Concatenate() يتم إنشاء إدخال CorruptedItem جديد. يمكن استخدام هذه الخاصية فقط عندما تكون قيمة CorruptedFileAction هي ConcatenateIgnoringCorrupted.

```csharp
//دمج Document وعرض معلومات حول Document المعطوبة
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


