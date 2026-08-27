---
title: "FormEditor.Single2Multiple"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor metod. Ändra ett enradigt textfält till ett flerradigt"
type: docs
weight: 350
url: /sv/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

Ändra ett enkellinjigt textfält till ett flerradigt.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det kvalificerade fältnamnet. |

### Returvärde

Om lyckat, returnera true; annars false.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


