---
title: SetSubmitFlag
second_title: Aspose.PDF för .NET API Referens
description: Ställ in skicka flagga för skicka knappen.
type: docs
weight: 370
url: /sv/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

Ställ in skicka flagga för skicka knappen.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namn på knappen Skicka. |
| submitFormFlag | SubmitFormFlag | Skicka flagga. |

### Returvärde

sant om fältet hittades och submit-flaggan har ställts in.

### Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### Se även

* enum [SubmitFormFlag](../../submitformflag)
* class [FormEditor](../../formeditor)
* namnutrymme [Aspose.Pdf.Facades](../../formeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
