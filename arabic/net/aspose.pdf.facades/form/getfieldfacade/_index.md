---
title: "Form.GetFieldFacade"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تُرجع كائن FrofmFieldFacade يحتوي على جميع سمات المظهر"
type: docs
weight: 210
url: /ar/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

يعيد كائن FrogmFieldFacade يحتوي على جميع سمات المظهر.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل للقراءة. |

### قيمة الإرجاع

كائن FormFieldFacade

### انظر أيضًا

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


