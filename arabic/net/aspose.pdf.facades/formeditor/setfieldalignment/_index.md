---
title: SetFieldAlignment
second_title: Aspose.PDF لمرجع .NET API
description: تعيين نمط المحاذاة لحقل نصي.
type: docs
weight: 300
url: /ar/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

تعيين نمط المحاذاة لحقل نصي.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل. |
| alignment | Int32 | تعريف نمط المحاذاة ، بما في ذلك FormFieldFacade.AlignLeft ، FormFieldFacade.AlignCenter و FormFieldFacade.AlignRight. |

### قيمة الإرجاع

صواب إذا تم العثور على الحقل وتعيين المحاذاة.

### أمثلة

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### أنظر أيضا

* class [FormEditor](../../formeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../formeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
