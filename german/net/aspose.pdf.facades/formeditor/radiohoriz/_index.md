---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Eigenschaft. Das Flag, um anzuzeigen, ob die Radios horizontal oder vertikal angeordnet sind, der Standardwert ist true
type: docs
weight: 80
url: /de/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz-Eigenschaft

Das Flag, um anzuzeigen, ob die Radios horizontal oder vertikal angeordnet sind, der Standardwert ist true.

```csharp
public bool RadioHoriz { get; set; }
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