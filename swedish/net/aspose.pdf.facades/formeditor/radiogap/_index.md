---
title: RadioGap
second_title: Aspose.PDF för .NET API Referens
description: Medlemmen som ska spela in gapet mellan två angränsande radioknappar i pixlar standard är 50.
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap property

Medlemmen som ska spela in gapet mellan två angränsande radioknappar i pixlar, standard är 50.

```csharp
public float RadioGap { get; set; }
```

### Exempel

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Se även

* class [FormEditor](../../formeditor)
* namnutrymme [Aspose.Pdf.Facades](../../formeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
