---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Setzen Sie den Ausrichtungsstil eines Textfelds
type: docs
weight: 260
url: /de/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment-Methode

Setzen Sie den Ausrichtungsstil eines Textfelds.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der qualifizierte Feldname. |
| alignment | Int32 | Die Definition des Ausrichtungsstils, einschließlich FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter und FormFieldFacade.AlignRight. |

### Rückgabewert

true, wenn das Feld gefunden wurde und die Ausrichtung gesetzt wurde.

## Beispiele

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)