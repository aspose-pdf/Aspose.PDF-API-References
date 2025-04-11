---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-egenskap. Flaggan för att ange om radion är ordnade horisontellt eller vertikalt, standardvärdet är sant
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz-egenskap

Flaggan för att indikera om radion är arrangerade horisontellt eller vertikalt, standardvärdet är sant.

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

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)