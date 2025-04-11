---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-metod. Ta bort objekt från listfältet
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem metod

Ta bort objekt från listfältet.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namnet på fältet. |
| itemName | Sträng | Namnet på objektet som måste tas bort. |

## Exempel

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)