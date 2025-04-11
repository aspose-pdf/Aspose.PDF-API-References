---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Element aus dem Listenfeld löschen
type: docs
weight: 180
url: /de/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem-Methode

Element aus dem Listenfeld löschen.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Feldes. |
| itemName | String | Name des Elements, das gelöscht werden muss. |

## Beispiele

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)