---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: خاصية FormEditor. العلامة للإشارة إلى ما إذا كانت أجهزة الراديو مرتبة أفقيًا أو عموديًا، القيمة الافتراضية هي true
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## خاصية FormEditor.RadioHoriz

العلامة للإشارة إلى ما إذا كانت أجهزة الراديو مرتبة أفقيًا أو عموديًا، القيمة الافتراضية هي true.

```csharp
public bool RadioHoriz { get; set; }
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