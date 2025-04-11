---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction enum. الإجراء المتخذ عند مواجهة ملف تالف في عملية الدمج
type: docs
weight: 4470
url: /ar/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

الإجراء المتخذ عند مواجهة ملف تالف في عملية الدمج.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| StopWithError | `0` | إذا تم مواجهة ملف تالف، توقف عن عملية الدمج وارجع خطأ. |
| ConcatenateIgnoringCorrupted | `1` | إذا تم مواجهة ملف تالف، فلا تتوقف عن الدمج ولا تعالج الملف التالف. قائمة الملفات التالفة متاحة في خاصية Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | عندما يتم مواجهة كائن تالف في الوثيقة المصدر، لن تتوقف العملية ويتم تجاهل الكائن التالف فقط. |

### See Also

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)