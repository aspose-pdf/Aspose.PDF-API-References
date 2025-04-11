---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تصدر محتوى حقول pdf إلى تدفق xml. لن يتم تصدير قيمة حقول الأزرار
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/form/exportxfdf/
---
## طريقة Form.ExportXfdf

تصدر محتوى حقول pdf إلى تدفق xml. لن يتم تصدير قيمة حقل الزر.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputXfdfStream | Stream | تدفق xml الناتج. |

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