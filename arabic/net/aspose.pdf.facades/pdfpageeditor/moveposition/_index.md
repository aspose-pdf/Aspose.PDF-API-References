---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfPageEditor. تنقل الأصل من 0 0 إلى النقطة المحددة. الأصل هو أسفل اليسار والوحدة هي نقطة 1 بوصة = 72 نقطة
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## طريقة PdfPageEditor.MovePosition

تنقل الأصل من (0, 0) إلى النقطة المحددة. الأصل هو أسفل اليسار والوحدة هي نقطة (1 بوصة = 72 نقطة).

```csharp
public void MovePosition(float moveX, float moveY)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| moveX | مفرد | إحداثي X. |
| moveY | مفرد | إحداثي Y. |

## أمثلة

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### انظر أيضًا

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)