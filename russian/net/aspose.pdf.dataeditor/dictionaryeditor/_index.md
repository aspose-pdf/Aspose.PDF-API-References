---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.DataEditor.DictionaryEditor. Класс для доступа к дереву словарей документа.
type: docs
weight: 3470
url: /ru/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## Класс DictionaryEditor

Класс для доступа к дереву словарей документа (словари документа, словари страниц, словари ресурсов).

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Свойства

| Название | Описание |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Полная коллекция ключей. Содержит редактируемые и не редактируемые ключи. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Получает количество элементов, содержащихся в `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Получает значение, указывающее, является ли `DictionaryEditor` только для чтения. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Получает или задает элемент с указанным ключом. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Коллекция редактируемых ключей. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Получает ICollection, содержащий значения в `DictionaryEditor`. |

## Методы

| Название | Описание |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Установить [`ICosPdfPrimitive`](../icospdfprimitive/) в словарь. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Установить [`ICosPdfPrimitive`](../icospdfprimitive/) в словарь. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Удаляет все элементы из `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Определяет, содержит ли `DictionaryEditor` конкретное значение. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Определяет, содержит ли `DictionaryEditor` элемент с указанным ключом. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Возвращает перечислитель, который перебирает коллекцию. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Удаляет первое вхождение конкретного объекта из `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Удаляет элемент с указанным ключом из `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | Для доступа к простым типам данных, таким как строка, имя, булево значение, число. Возвращает null для других типов. |

### См. также

* интерфейс [ICosPdfPrimitive](../icospdfprimitive/)
* пространство имен [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* сборка [Aspose.PDF](../../)