---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: FormEditor property. The member to record the gap between two neighboring radio buttons in pixelsdefault is 50
type: docs
weight: 70
url: /net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap property

The member to record the gap between two neighboring radio buttons in pixels,default is 50.

```csharp
public float RadioGap { get; set; }
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


