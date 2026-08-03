---
title: "FormEditor.RadioGap"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor egenskap. Medlemmen som registrerar avståndet mellan två intilliggande radioknappar i pixlar, standard är 50"
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap property

Medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50.

```csharp
public float RadioGap { get; set; }
```

## Exempel

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


