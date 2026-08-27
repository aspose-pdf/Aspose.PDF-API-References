---
title: "FormEditor.RadioButtonItemSize"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية FormEditor. تحصل أو تعيين حجم عنصر زر الاختيار عندما يتم إضافة حقل زر اختيار جديد"
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## FormEditor.RadioButtonItemSize property

يحصل أو يضبط حجم عنصر زر الاختيار (عند إضافة حقل زر اختيار جديد).

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.RadioButtonItemSize = 20;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public double RadioButtonItemSize { get; set; }
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


