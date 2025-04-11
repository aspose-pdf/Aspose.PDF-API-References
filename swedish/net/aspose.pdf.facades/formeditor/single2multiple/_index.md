---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metod. Ändra ett enradigt textfält till ett flerradigt.
type: docs
weight: 350
url: /sv/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple metod

Ändra ett enradigt textfält till ett flerradigt.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det kvalificerade fältnamnet. |

### Returvärde

Om framgång, returnera true; annars false.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)