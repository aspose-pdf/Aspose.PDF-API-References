---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Ändern Sie den Namen des Feldes
type: docs
weight: 230
url: /de/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField-Methode

Ändern Sie den Namen des Feldes.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Alter Name des Feldes. |
| newFieldName | String | Neuer Name des Feldes. |

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)