---
title: FormEditor.RadioButtonItemSize
second_title: Aspose.PDF for .NET API Reference
description: خاصية FormEditor. تحصل أو تعين حجم عنصر زر الراديو عند إضافة حقل زر راديو جديد
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## خاصية FormEditor.RadioButtonItemSize

تحصل أو تعين حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد).

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