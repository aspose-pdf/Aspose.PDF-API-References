---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تستورد محتوى الحقول من ملف xfdfxml وتضعه في ملف pdf الجديد
type: docs
weight: 300
url: /ar/net/aspose.pdf.facades/form/importxfdf/
---
## طريقة Form.ImportXfdf

تستورد محتوى الحقول من ملف xfdf(xml) وتضعه في ملف pdf الجديد.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputXfdfStream | Stream | تدفق xfdf(xml) المدخل. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)