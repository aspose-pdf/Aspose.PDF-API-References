---
title: "FormEditor.DelListItem"
second_title: "Справочник API Aspose.PDF для .NET"
description: "метод FormEditor. Удалить элемент из поля списка"
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/formeditor/dellistitem/
---
## FormEditor.DelListItem method

Удаляет элемент из поля списка.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля. |
| itemName | String | Имя элемента, который необходимо удалить. |

## Примеры

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


