---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metod. Ta bort skicka åtgärd för fältet
type: docs
weight: 220
url: /sv/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction metod

Ta bort skicka åtgärd för fältet.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namn på fältet. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)