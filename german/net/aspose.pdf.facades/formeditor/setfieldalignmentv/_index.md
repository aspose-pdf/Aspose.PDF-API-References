---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Setzen Sie den vertikalen Ausrichtungsstil eines Textfelds
type: docs
weight: 270
url: /de/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV-Methode

Setzen Sie den vertikalen Ausrichtungsstil eines Textfelds.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der qualifizierte Feldname. |
| alignment | Int32 | Die Definition des Ausrichtungsstils, einschließlich FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle und FormFieldFacade.AlignRight. |

### Rückgabewert

true, wenn das Feld gefunden wurde und die Ausrichtung erfolgreich festgelegt wurde.

## Beispiele

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)