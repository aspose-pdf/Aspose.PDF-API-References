---
title: "FormEditor.RemoveFieldAction"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-metod. Ta bort skicka-in-åtgärd för fältet"
type: docs
weight: 220
url: /sv/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction method

Ta bort skicka‑åtgärd för fältet.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältets namn. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


