---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تعيد كائن FrofmFieldFacade الذي يحتوي على جميع سمات المظهر
type: docs
weight: 210
url: /ar/net/aspose.pdf.facades/form/getfieldfacade/
---
## طريقة Form.GetFieldFacade

تعيد كائن FrofmFieldFacade الذي يحتوي على جميع سمات المظهر.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل للقراءة. |

### قيمة الإرجاع

كائن FormFieldFacade

### انظر أيضًا

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)