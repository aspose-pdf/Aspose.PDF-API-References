---
title: GetFieldFacade
second_title: Aspose.PDF لمرجع .NET API
description: إرجاع كائن FrofmFieldFacade يحتوي على كافة سمات المظهر.
type: docs
weight: 240
url: /ar/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

إرجاع كائن FrofmFieldFacade يحتوي على كافة سمات المظهر.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldName | String | اسم المجال للقراءة. |

### قيمة الإرجاع

كائن FormFieldFacade

### أنظر أيضا

* class [FormFieldFacade](../../formfieldfacade)
* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
