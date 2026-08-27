---
title: "FormEditor.AddListItem"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Добавляет новый элемент в список"
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
| fieldName | String | Имя поля, к которому будет добавлен новый элемент. |
| itemName | String | Имя нового элемента. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Добавить новый элемент с экспортным значением в существующее поле списка, только для поля комбобокса AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, к которому будут добавлены элементы. |
| exportName | String[] | Массив строк, обозначающий новый элемент списка с экспортируемым значением, т.е. (Метка элемента, Экспортируемое значение). |

## Примеры

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


