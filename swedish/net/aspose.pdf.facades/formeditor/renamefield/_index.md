---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metod. Ändra namn på fältet
type: docs
weight: 230
url: /sv/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField metod

Ändra namn på fältet.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Gamla namnet på fältet. |
| newFieldName | String | Nya namnet på fältet. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)