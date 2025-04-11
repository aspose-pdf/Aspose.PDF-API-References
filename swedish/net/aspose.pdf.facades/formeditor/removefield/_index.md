---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-metod. Ta bort fältet från formuläret
type: docs
weight: 210
url: /sv/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField metod

Ta bort fält från formuläret.

```csharp
public void RemoveField(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namnet på fältet som måste tas bort. |

## Exempel

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)