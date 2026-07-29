---
title: "التعداد PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "التعداد Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction. الإجراء الذي يتم عندما يُصادف ملف تالف أثناء عملية الدمج"
type: docs
weight: 4590
url: /ar/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

الإجراء الذي يتم عندما يُصادف ملف تالف أثناء عملية الدمج.

```csharp
public enum ConcatenateCorruptedFileAction
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| StopWithError | `0` | إذا تم مواجهة ملف تالف، فقم بإيقاف عملية الدمج وأرجع خطأ. |
| ConcatenateIgnoringCorrupted | `1` | إذا تم مواجهة ملف تالف، فلا توقف عملية الدمج ولا تعالج الملف التالف. قائمة الملفات التالفة متاحة في الخاصية Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | عند مواجهة كائن تالف في المستند المصدر، لن تتوقف العملية وسيتم تجاهل الكائن التالف فقط. |

### انظر أيضًا

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


