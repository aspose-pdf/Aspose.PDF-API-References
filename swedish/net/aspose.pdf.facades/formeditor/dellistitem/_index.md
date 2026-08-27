---
title: "FormEditor.DelListItem"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor metod. Ta bort ett objekt från listfältet"
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

Ta bort objekt från listfältet.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältets namn. |
| itemName | String | Namnet på det objekt som måste tas bort. |

## Exempel

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


