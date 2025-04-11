---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تعيين نمط المحاذاة الرأسية لحقل نصي
type: docs
weight: 270
url: /ar/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## طريقة FormEditor.SetFieldAlignmentV

تعيين نمط المحاذاة الرأسية لحقل نصي.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل. |
| alignment | Int32 | تعريف نمط المحاذاة، بما في ذلك FormFieldFacade.AlignTop و FormFieldFacade.AlignMiddle و FormFieldFacade.AlignRight. |

### قيمة الإرجاع

true إذا تم العثور على الحقل وتم ملء المحاذاة بنجاح.

## أمثلة

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)