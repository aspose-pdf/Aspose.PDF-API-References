---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.PageCollection. Коллекция страниц PDF документа
type: docs
weight: 8080
url: /ru/net/aspose.pdf/pagecollection/
---
## Класс PageCollection

Коллекция страниц PDF документа.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Получает количество страниц в документе. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Получает значение, указывающее, что коллекция является только для чтения. Всегда возвращает false. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Возвращает true, если объект синхронизирован. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Получает страницу по индексу. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Получает объект синхронизации коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Принимает объект посетителя [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/), который предоставляет функциональность для работы с аннотациями. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Принимает объект посетителя [`ImagePlacementAbsorber`](../imageplacementabsorber/), который предоставляет функциональность для работы с объектами размещения изображений. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Принимает объект посетителя [`TextAbsorber`](../../aspose.pdf.text/textabsorber/), который предоставляет функциональность для работы с текстовыми объектами. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Принимает объект посетителя [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/), который предоставляет функциональность для работы с текстовыми объектами. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Добавляет пустую страницу. Если документ уже содержит страницы с различными размерами, будет выбрана размерность наиболее часто встречающейся страницы. В случае, если есть только две разные страницы, будет использован размер первой страницы. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Добавляет в коллекцию все страницы из списка. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Добавляет страницу в коллекцию. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Добавляет в коллекцию все страницы из массива. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Очищает коллекцию страниц. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Определяет, содержит ли этот экземпляр объект. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Копирует страницы в документ. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Удаляет все страницы из коллекции. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Удаляет указанную страницу. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Удаляет страницы, номера которых указаны в массиве. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Удаляет все поля, расположенные на страницах, и помещает их значения вместо этого. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Очищает кэшированные данные |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Возвращает перечислитель страниц. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Возвращает индекс указанной страницы. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Вставляет пустую страницу в коллекцию в указанной позиции. Если документ уже содержит страницы с различными размерами, будет выбрана размерность наиболее часто встречающейся страницы. В случае, если есть только две разные страницы, будет использован размер первой страницы. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Вставляет страницы из коллекции в документ. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Вставляет страницу в коллекцию страниц в указанном месте. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Вставляет страницы массива в документ. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Удаляет указанный элемент, вызывает NotSupportedException. |

### См. также

* класс [Page](../page/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)