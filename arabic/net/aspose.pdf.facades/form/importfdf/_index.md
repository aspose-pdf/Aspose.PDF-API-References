---
title: ImportFdf
second_title: Aspose.PDF لمرجع .NET API
description: يستورد محتوى الحقول من ملف fdf ويضعها في ملف pdf الجديد.
type: docs
weight: 310
url: /ar/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

يستورد محتوى الحقول من ملف fdf ويضعها في ملف pdf الجديد.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFdfStream | Stream | دفق fdf المدخلات. |

### أمثلة

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
