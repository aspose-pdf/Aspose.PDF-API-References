---
title: "Form.GetFieldType"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تُرجع نوع الحقل"
type: docs
weight: 240
url: /ar/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType method

يعيد نوع الحقل.

```csharp
public FieldType GetFieldType(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل. |

### قيمة الإرجاع

عنصر من تعداد FileType المقابل لنوع الحقل.

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


