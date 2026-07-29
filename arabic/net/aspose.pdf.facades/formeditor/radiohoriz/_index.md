---
title: "FormEditor.RadioHoriz"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية FormEditor. العلامة التي تشير إلى ما إذا كانت أزرار الراديو مرتبة أفقياً أو عمودياً، القيمة الافتراضية هي true."
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz property

العلم للإشارة إلى ما إذا كانت أزرار الاختيار مرتبة أفقياً أم عمودياً، القيمة الافتراضية هي true.

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


