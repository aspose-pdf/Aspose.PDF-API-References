---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Добавляет новый элемент в список
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Добавляет новый элемент в список.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, в которое будет добавлен новый элемент. |
| itemName | String | Имя нового элемента. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Добавляет новый элемент с экспортным значением в существующее поле списка, только для поля комбинированного поля AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, в которое будут добавлены элементы. |
| exportName | String[] | Массив строк, обозначающий новый элемент списка с экспортным значением, т.е. (Метка элемента, Экспортное значение). |

## Примеры

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)