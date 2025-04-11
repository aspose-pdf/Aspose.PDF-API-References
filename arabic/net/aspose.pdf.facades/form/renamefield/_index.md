---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تعيد تسمية حقل. إما حقل AcroForm أو حقل XFA مقبول
type: docs
weight: 330
url: /ar/net/aspose.pdf.facades/form/renamefield/
---
## طريقة Form.RenameField

تعيد تسمية حقل. إما حقل AcroForm أو حقل XFA مقبول.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل القديم |
| newFieldName | سلسلة | اسم الحقل الجديد |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### انظر أيضًا

* الفئة [Form](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)