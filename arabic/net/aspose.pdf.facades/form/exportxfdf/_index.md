---
title: ExportXfdf
second_title: Aspose.PDF لمرجع .NET API
description: يصدر محتوى حقول ملف pdf إلى تيار xml . لن يتم تصدير قيمة حقل الزر.
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf method

يصدر محتوى حقول ملف pdf إلى تيار xml . لن يتم تصدير قيمة حقل الزر.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputXfdfStream | Stream | تيار xml الناتج. |

### أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->