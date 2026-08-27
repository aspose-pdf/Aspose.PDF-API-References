---
title: "Form.ImportXfdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تستورد محتوى الحقول من ملف xfdfxml وتضعه في ملف PDF الجديد."
type: docs
weight: 300
url: /ar/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

يستورد محتوى الحقول من ملف xfdf(xml) ويضعها في ملف pdf الجديد.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputXfdfStream | Stream | تدفق xfdf(xml) الإدخال. |

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


