---
title: FormEditor.DelListItem
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Удалить элемент из списка
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/formeditor/dellistitem/
---
## Метод FormEditor.DelListItem

Удалить элемент из списка.

```csharp
public void DelListItem(string fieldName, string itemName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля. |
| itemName | String | Имя элемента, который должен быть удален. |

## Примеры

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
formEditor.DelListItem("listboxField", "item2");
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)