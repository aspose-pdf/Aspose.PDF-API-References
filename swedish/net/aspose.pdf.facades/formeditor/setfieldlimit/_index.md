---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-metod. Ställer in maximalt teckenantal för textfältet
type: docs
weight: 310
url: /sv/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit metod

Ställer in maximalt teckenantal för textfältet.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namn på textfältet. |
| fieldLimit | Int32 | Nytt värde för begränsningen av fältet. |

### Returvärde

true om fältbegränsningen har ställts in framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)