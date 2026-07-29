---
title: "Form.RenameField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تعيد تسمية حقل. سواء كان حقل AcroForm أو حقل XFA مقبول."
type: docs
weight: 330
url: /ar/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

يعيد تسمية حقل. سواء كان حقل AcroForm أو حقل XFA مقبول.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل القديم |
| newFieldName | String | اسم الحقل الجديد |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


