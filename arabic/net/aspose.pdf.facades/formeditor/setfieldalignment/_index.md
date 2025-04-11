---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تعيين نمط محاذاة حقل النص
type: docs
weight: 260
url: /ar/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## طريقة FormEditor.SetFieldAlignment

تعيين نمط محاذاة حقل النص.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل. |
| alignment | Int32 | تعريف نمط المحاذاة، بما في ذلك FormFieldFacade.AlignLeft و FormFieldFacade.AlignCenter و FormFieldFacade.AlignRight. |

### قيمة الإرجاع

true إذا تم العثور على الحقل وتم تعيين المحاذاة.

## أمثلة

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)