---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تستورد محتوى الحقول من ملف fdf وتضعه في ملف pdf الجديد
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/form/importfdf/
---
## طريقة Form.ImportFdf

تستورد محتوى الحقول من ملف fdf وتضعه في ملف pdf الجديد.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFdfStream | Stream | تدفق fdf المدخل. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)