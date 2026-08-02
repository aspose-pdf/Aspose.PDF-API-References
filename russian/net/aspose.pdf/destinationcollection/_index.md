---
title: "Класс DestinationCollection"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.DestinationCollection класс. Класс представляет коллекцию всех назначений, дерево имён, сопоставляющее строки имён с назначениями; см. 12.3.2.3 Named Destinations и 7.7.4 Name Dictionary в PDF‑документе."
type: docs
weight: 3630
url: /ru/net/aspose.pdf/destinationcollection/
---
## DestinationCollection class

Класс представляет коллекцию всех назначений (дерево имён, сопоставляющее строки имён с назначениями (см. 12.3.2.3, "Named Destinations") и (см. 7.7.4, "Name Dictionary")) в pdf‑документе.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Получает количество элементов, содержащихся в коллекции. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | Получает объект назначения по индексу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Добавляет указанный элемент. Коллекция только для чтения. Всегда генерирует исключение NotSupportedException. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | Коллекция только для чтения. Всегда генерирует исключение NotSupportedException. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Определяет, содержит ли данный экземпляр объект. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Возвращает перечислитель. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | Возвращает явное назначение по имени. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | Возвращает номер страницы назначения по имени. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Возвращает индекс назначения в коллекции. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Удаляет указанный элемент. Коллекция только для чтения. Всегда генерирует исключение NotSupportedException. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


