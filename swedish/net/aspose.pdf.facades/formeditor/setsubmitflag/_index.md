---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metod. Ställ in skicka flagga för skicka knapp
type: docs
weight: 330
url: /sv/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag metod

Ställ in skicka flagga för skicka knapp.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namn på skicka knapp. |
| submitFormFlag | SubmitFormFlag | Skicka flagga. |

### Returvärde

true om fältet hittades och skicka flaggan ställdes in framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### Se Även

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)