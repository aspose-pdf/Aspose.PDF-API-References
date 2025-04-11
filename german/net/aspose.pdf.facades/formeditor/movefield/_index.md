---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Setzen Sie die neue Position des Feldes
type: docs
weight: 200
url: /de/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField-Methode

Setzen Sie die neue Position des Feldes.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Feldes, das verschoben werden muss. |
| llx | Single | Abszisse der unteren linken Ecke des Feldes. |
| lly | Single | Ordinate der unteren linken Ecke des Feldes. |
| urx | Single | Abszisse der oberen rechten Ecke des Feldes. |
| ury | Single | Ordinate der oberen rechten Ecke des Feldes. |

### Rückgabewert

true, wenn die Feldposition erfolgreich geändert wurde.

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)