---
title: Class DestinationCollection
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.DestinationCollection. Класс представляет собой коллекцию всех назначений (дерево имен, сопоставляющее строковые имена с назначениями, см. 12.3.2.3 "Названные назначения" и см. 7.7.4 "Словарь имен") в документе pdf.
type: docs
weight: 3510
url: /ru/net/aspose.pdf/destinationcollection/
---
## Класс DestinationCollection

Класс представляет собой коллекцию всех назначений (дерево имен, сопоставляющее строковые имена с назначениями (см. 12.3.2.3, "Названные назначения") и (см. 7.7.4, "Словарь имен")) в документе pdf.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Получает количество элементов, содержащихся в коллекции. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Получает значение, указывающее, является ли коллекция только для чтения. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | Получает объект назначения по индексу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Добавляет указанный элемент. Коллекция только для чтения. Всегда вызывает исключение NotSupportedException. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | Коллекция только для чтения. Всегда вызывает исключение NotSupportedException. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Определяет, содержит ли этот экземпляр объект. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Возвращает перечислитель. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | Возвращает явное назначение по имени. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | Возвращает номер страницы назначения по имени. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Возвращает индекс назначения в коллекции. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Удаляет указанный элемент. Коллекция только для чтения. Всегда вызывает исключение NotSupportedException. |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)