---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تعيد نوع الحقل
type: docs
weight: 240
url: /ar/net/aspose.pdf.facades/form/getfieldtype/
---
## طريقة Form.GetFieldType

تعيد نوع الحقل.

```csharp
public FieldType GetFieldType(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل. |

### قيمة الإرجاع

عنصر من تعداد FileType يتوافق مع نوع الحقل.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### انظر أيضًا

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)