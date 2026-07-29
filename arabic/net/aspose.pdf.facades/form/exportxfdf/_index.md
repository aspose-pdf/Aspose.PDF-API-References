---
title: "Form.ExportXfdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تصدر محتوى حقول الـ pdf إلى تدفق xml. لن يتم تصدير قيمة حقول الأزرار"
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf method

يصدّر محتوى حقول الـ pdf إلى تدفق XML. لن يتم تصدير قيمة حقل الزر.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputXfdfStream | Stream | تدفق XML الناتج. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


