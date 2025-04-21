---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تملأ حقول مربع النص بقيم نصية وتقوم بحفظ المستند. ذات صلة بالمستندات الموقعة. ملاحظة تنطبق فقط على مربع النص. كل من أسماء الحقول والقيم حساسة لحالة الأحرف.
type: docs
weight: 140
url: /ar/net/aspose.pdf.facades/form/fillfields/
---
## طريقة Form.FillFields

تملأ حقول مربع النص بقيم نصية وتقوم بحفظ المستند. ذات صلة بالمستندات الموقعة. ملاحظة: تنطبق فقط على مربع النص. كل من أسماء الحقول والقيم حساسة لحالة الأحرف.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldNames | String[] | أسماء الحقول. |
| fieldValues | String[] | القيم الجديدة للحقول. |
| output | Stream& | التدفق الذي سيتم حفظ المستند فيه. |

### قيمة الإرجاع

true إذا تم العثور على الحقول وتم ملؤها بنجاح.

## أمثلة

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)