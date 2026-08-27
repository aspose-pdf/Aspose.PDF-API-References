---
title: "Form.ImportFdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تستورد محتوى الحقول من ملف fdf وتضعه في ملف pdf الجديد."
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

يستورد محتوى الحقول من ملف fdf ويضعها في ملف pdf الجديد.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFdfStream | Stream | دفق fdf الإدخال. |

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


