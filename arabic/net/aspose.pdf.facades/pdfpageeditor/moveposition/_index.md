---
title: "PdfPageEditor.MovePosition"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfPageEditor. تنقل الأصل من 0 0 إلى النقطة المحددة. الأصل هو أسفل اليسار والوحدة هي point 1 بوصة = 72 نقطة"
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

ينقل الأصل من (0, 0) إلى النقطة المحددة. الأصل هو أسفل اليسار والوحدة هي النقطة (1 بوصة = 72 نقطة).

```csharp
public void MovePosition(float moveX, float moveY)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| moveX | Single | الإحداثي X. |
| moveY | Single | الإحداثي Y. |

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


