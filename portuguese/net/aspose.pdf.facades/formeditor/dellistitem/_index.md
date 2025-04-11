---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Excluir item do campo de lista
type: docs
weight: 180
url: /pt/net/aspose.pdf.facades/formeditor/dellistitem/
---
## Método FormEditor.DelListItem

Excluir item do campo de lista.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo. |
| itemName | String | Nome do item que deve ser excluído. |

## Exemplos

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)