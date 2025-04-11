---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تعيد علامات الحقل
type: docs
weight: 220
url: /ar/net/aspose.pdf.facades/form/getfieldflag/
---
## طريقة Form.GetFieldFlag

تعيد علامات الحقل.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل |

### قيمة الإرجاع

علامة الخاصية (للقراءة فقط / مطلوبة / لا تصدير

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