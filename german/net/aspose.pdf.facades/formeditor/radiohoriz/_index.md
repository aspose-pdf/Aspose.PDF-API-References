---
title: RadioHoriz
second_title: Aspose.PDF für .NET-API-Referenz
description: Das Flag das angibt ob die Funkgeräte horizontal oder vertikal angeordnet sind der Standardwert ist wahr.
type: docs
weight: 100
url: /de/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz property

Das Flag, das angibt, ob die Funkgeräte horizontal oder vertikal angeordnet sind, der Standardwert ist wahr.

```csharp
public bool RadioHoriz { get; set; }
```

### Beispiele

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Siehe auch

* class [FormEditor](../../formeditor)
* namensraum [Aspose.Pdf.Facades](../../formeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
