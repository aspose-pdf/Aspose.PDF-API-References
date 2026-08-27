---
title: "FormEditor.RenameField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor metod. Ändra namn på fältet"
type: docs
weight: 230
url: /sv/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField method

Ändra namn på fältet.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Gammalt namn på fältet. |
| newFieldName | String | Nytt namn på fältet. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


