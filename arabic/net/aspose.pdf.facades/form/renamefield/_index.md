---
title: RenameField
second_title: Aspose.PDF لمرجع .NET API
description: يعيد تسمية حقل. إما حقل AcroForm أو حقل XFA على ما يرام.
type: docs
weight: 350
url: /ar/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

يعيد تسمية حقل. إما حقل AcroForm أو حقل XFA على ما يرام.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل القديم |
| newFieldName | String | اسم الحقل الجديد |

### أمثلة

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->