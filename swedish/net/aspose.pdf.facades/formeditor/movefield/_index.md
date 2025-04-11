---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-metod. Ställ in ny position för fält
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField metod

Ställ in ny position för fältet.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namn på fältet som måste flyttas. |
| llx | Enkel | Abscissa för det nedre vänstra hörnet av fältet. |
| lly | Enkel | Ordinate för det nedre vänstra hörnet av fältet. |
| urx | Enkel | Abscissa för det övre högra hörnet av fältet. |
| ury | Enkel | Ordinate för det övre högra hörnet av fältet. |

### Returvärde

true om fältets position ändrades framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)