---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Eigenschaft. Das Mitglied zur Aufzeichnung des Abstands zwischen zwei benachbarten Optionsfeldern in Pixeln, Standard ist 50
type: docs
weight: 70
url: /de/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap-Eigenschaft

Das Mitglied zur Aufzeichnung des Abstands zwischen zwei benachbarten Optionsfeldern in Pixeln, Standard ist 50.

```csharp
public float RadioGap { get; set; }
```

## Beispiele

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)