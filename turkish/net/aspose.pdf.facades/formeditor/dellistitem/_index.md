---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Liste alanından öğe sil
type: docs
weight: 180
url: /tr/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem metodu

Liste alanından öğe silin.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Alanın adı. |
| itemName | String | Silinmesi gereken öğenin adı. |

## Örnekler

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)