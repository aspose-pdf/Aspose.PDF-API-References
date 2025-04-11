---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: خاصية FormEditor. العضو لتسجيل الفجوة بين زرين راديو متجاورين بالبكسل، القيمة الافتراضية هي 50
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/formeditor/radiogap/
---
## خاصية FormEditor.RadioGap

العضو لتسجيل الفجوة بين زرين راديو متجاورين بالبكسل، القيمة الافتراضية هي 50.

```csharp
public float RadioGap { get; set; }
```

## أمثلة

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)