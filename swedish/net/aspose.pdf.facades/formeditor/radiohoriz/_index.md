---
title: "FormEditor.RadioHoriz"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor‑egenskap. Flaggan som indikerar om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true"
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz property

Flaggan som indikerar om radioknapparna är ordnade horisontellt eller vertikalt, standardvärdet är true.

```csharp
public bool RadioHoriz { get; set; }
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


