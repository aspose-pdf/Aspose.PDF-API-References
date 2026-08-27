---
title: "FormEditor.MoveField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor metod. Ställ in ny position för fältet"
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField method

Ställ in ny position för fältet.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namn på fältet som måste flyttas. |
| llx | Single | Abskissa för fältets nedre vänstra hörn. |
| lly | Single | Ordinat för fältets nedre vänstra hörn. |
| urx | Single | Abskissa för fältets övre högra hörn. |
| ury | Single | Ordinat för fältets övre högra hörn. |

### Returvärde

Sant om fältpositionen ändrades framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


