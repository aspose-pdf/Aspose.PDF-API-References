---
title: Single2Multiple
second_title: Aspose.PDF för .NET API Referens
description: Ändra ett enkelradigt textfält till ett flerradigt.
type: docs
weight: 390
url: /sv/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

Ändra ett enkelradigt textfält till ett flerradigt.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det kvalificerade fältnamnet. |

### Returvärde

Om det lyckas, returnera sant; annars falskt.

### Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Se även

* class [FormEditor](../../formeditor)
* namnutrymme [Aspose.Pdf.Facades](../../formeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->