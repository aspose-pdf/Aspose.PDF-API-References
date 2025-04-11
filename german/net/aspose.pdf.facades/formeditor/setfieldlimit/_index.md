---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Setzt die maximale Zeichenanzahl des Textfelds
type: docs
weight: 310
url: /de/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit-Methode

Setzt die maximale Zeichenanzahl des Textfelds.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Textfelds. |
| fieldLimit | Int32 | Neuer Wert des Limits für das Feld. |

### Rückgabewert

true, wenn das Feldlimit erfolgreich gesetzt wurde.

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)