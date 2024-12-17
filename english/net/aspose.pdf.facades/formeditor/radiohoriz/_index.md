---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: FormEditor property. The flag to indicate whether the radios are arranged horizontally or vertically default value is true
type: docs
weight: 80
url: /net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz property

The flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

```csharp
public bool RadioHoriz { get; set; }
```

## Examples

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


