---
title: "Класс PageCollection"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.PageCollection. Коллекция страниц PDF‑документа"
type: docs
weight: 8220
url: /ru/net/aspose.pdf/pagecollection/
---
## PageCollection class

Коллекция страниц PDF document.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Получает количество страниц в документе. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Получает значение, указывающее, является ли коллекция только для чтения. Всегда возвращает false. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Возвращает true, если объект синхронизирован. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Получает страницу по индексу. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Получает объект синхронизации коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Принимает объект‑посетитель [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/), предоставляющий функциональность для работы с аннотациями. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Принимает объект‑посетитель [`ImagePlacementAbsorber`](../imageplacementabsorber/), предоставляющий функциональность для работы с объектами размещения изображений. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Принимает объект‑посетитель [`TextAbsorber`](../../aspose.pdf.text/textabsorber/), предоставляющий функциональность для работы с текстовыми объектами. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Принимает объект‑посетитель [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/), предоставляющий функциональность для работы с текстовыми объектами. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Добавляет пустую страницу. Если документ уже содержит страницы разных размеров, будет выбран размер наиболее часто встречающейся страницы. В случае, когда существует только две разные страницы, будет использован размер первой страницы. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Добавляет в коллекцию все страницы из списка. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Добавляет страницу в коллекцию. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Добавляет в коллекцию все страницы из массива. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Очистить коллекцию страниц. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Определяет, содержит ли данный экземпляр объект. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Копирует страницы в документ. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Удаляет все страницы из коллекции. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Удалить указанную страницу. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Удалить страницы, номера которых указаны в массиве. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Удаляет все поля, расположенные на страницах, и вместо них размещает их значения. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Очищает кэшированные данные |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Возвращает перечислитель страниц. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Возвращает индекс указанной страницы. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Вставить пустую страницу в коллекцию в указанную позицию. Если документ уже содержит страницы разного размера, будет выбран размер наиболее часто встречающейся страницы. В случае, когда существует только две разные страницы, будет использован размер первой страницы. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Вставляет страницы из коллекции в документ. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Вставляет страницу в коллекцию страниц в указанное место. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Вставляет страницы из массива в документ. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Удаляет указанный элемент, бросает NotSupportedException. |

### См. также

* class [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


