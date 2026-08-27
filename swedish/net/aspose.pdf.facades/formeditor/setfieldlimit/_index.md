---
title: "FormEditor.SetFieldLimit"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-metod. Ställer in maximalt teckenantal för textfältet"
type: docs
weight: 310
url: /sv/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

Ställer in maximalt teckenantal för textfältet.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namnet på textfältet. |
| fieldLimit | Int32 | Nytt värde för gränsen för fältet. |

### Returvärde

true om fältgränsen sattes framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


