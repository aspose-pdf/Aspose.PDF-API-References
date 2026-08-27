---
title: "FormEditor.RemoveField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor metod. Ta bort fält från formuläret"
type: docs
weight: 210
url: /sv/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

Ta bort fält från formuläret.

```csharp
public void RemoveField(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namn på fältet som måste tas bort. |

## Exempel

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


