---
title: "Form.FillFields"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تملأ حقول مربعات النص بقيم نصية وتحفظ المستند. ذات صلة بالمستندات الموقعة. ملاحظة: تُطبق فقط على مربعات النص. كل من أسماء الحقول والقيم حساسة لحالة الأحرف"
type: docs
weight: 140
url: /ar/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields method

يملى حقول مربع النص بقيم نصية ويحفظ المستند. يتعلق بالمستندات الموقعة. ملاحظة: يُطبق فقط على مربع النص. كل من أسماء الحقول والقيم حساسة لحالة الأحرف.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldNames | String[] | أسماء الحقول. |
| fieldValues | String[] | القيم الجديدة للحقول. |
| الإخراج | Stream& | التدفق حيث سيتم حفظ المستند. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقول وتعبئتها بنجاح.

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


