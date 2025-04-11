---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Setzen Sie das Submit-Flag des Submit-Buttons
type: docs
weight: 330
url: /de/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag-Methode

Setzen Sie das Submit-Flag des Submit-Buttons.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Submit-Buttons. |
| submitFormFlag | SubmitFormFlag | Submit-Flag. |

### Rückgabewert

true, wenn das Feld gefunden wurde und das Submit-Flag erfolgreich gesetzt wurde.

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### Siehe auch

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)