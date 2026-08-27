---
title: "Form.GetFieldFlag"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تُرجع أعلام الحقل"
type: docs
weight: 220
url: /ar/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag method

يعيد علامات الحقل.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل |

### قيمة الإرجاع

علامة الخاصية (ReadOnly/ Required/NoExport

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### انظر أيضًا

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


