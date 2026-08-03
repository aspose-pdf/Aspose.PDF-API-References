---
title: "FormEditor.SetSubmitFlag"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-metod. Ställer in submit-flaggan för submit-knappen"
type: docs
weight: 330
url: /sv/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

Ställ in submit‑flaggan för submit‑knappen.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namnet på submit-knappen. |
| submitFormFlag | SubmitFormFlag | Submit-flagga. |

### Returvärde

true om fältet hittades och submit-flaggan sattes framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### Se även

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


