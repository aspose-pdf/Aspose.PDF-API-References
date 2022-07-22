---
title: OutlineItemCollection
second_title: Aspose.PDF для справочника API .NET
description: Представляет запись схемы в иерархии структуры документа PDF.
type: docs
weight: 5770
url: /ru/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

Представляет запись схемы в иерархии структуры документа PDF.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection)(OutlineCollection) | Инициализирует экземпляр элемента структуры, используя объект корневой иерархии. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action) { get; set; } | Получает или задает действие для этого элемента схемы. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold) { get; set; } | Получает или устанавливает полужирный флаг для текста заголовка этого элемента схемы |
| [Color](../../aspose.pdf/outlineitemcollection/color) { get; set; } | Получает или задает цвет текста заголовка этого элемента схемы. |
| override [Count](../../aspose.pdf/outlineitemcollection/count) { get; } | Количество предметов коллекции. Пожалуйста, не путайте с VisibleCount: VisibleCount получает количество видимых элементов схемы на всех уровнях. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination) { get; set; } | Получает или задает место назначения для этого элемента схемы. |
| [First](../../aspose.pdf/outlineitemcollection/first) { get; } | Получает элемент схемы, представляющий первый элемент верхнего уровня в иерархии структуры. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext) { get; } | Проверить, представляет ли элемент структуры следующий элемент относительно этого элемента в иерархии структуры. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly) { get; } | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized) { get; } | Получает значение, указывающее, является ли доступ к этой коллекции синхронизированным (потокобезопасным). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic) { get; set; } | Получает или устанавливает флаг курсива для текста заголовка этого элемента схемы |
| [Item](../../aspose.pdf/outlineitemcollection/item) { get; } | Получает элемент структуры из коллекции, используя index. |
| [Last](../../aspose.pdf/outlineitemcollection/last) { get; } | Получает элемент схемы, представляющий последний элемент верхнего уровня в иерархии структуры. |
| [Level](../../aspose.pdf/outlineitemcollection/level) { get; } | Получает уровень иерархии элемента схемы. |
| [Next](../../aspose.pdf/outlineitemcollection/next) { get; } | Получает элемент схемы, представляющий следующий элемент относительно этого элемента в иерархии схемы. |
| [Open](../../aspose.pdf/outlineitemcollection/open) { get; set; } | Получить или установить открытый статус (true/false) для элемента схемы. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent) { get; } | Получает родительский объект этого элемента схемы в иерархии структуры. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev) { get; } | Получает элемент схемы, представляющий предыдущий элемент относительно этого элемента в иерархии схемы. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot) { get; } | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |
| [Title](../../aspose.pdf/outlineitemcollection/title) { get; set; } | Получает или задает заголовок для этого элемента схемы. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount) { get; } | Получает общее количество элементов схемы на всех уровнях иерархии структуры документа. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add)(OutlineItemCollection) | Добавляет элемент схемы в коллекцию. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear)() | Удаляет все элементы из коллекции. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains)(OutlineItemCollection) | Проверяет, содержит ли коллекция данный элемент. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto)(OutlineItemCollection[], int) | Копирует элементы схемы в System.Array, начиная с определенного индекса System.Array. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete#delete)() | Удаляет этот элемент схемы из иерархии структуры документа. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete#delete_1)(string) | Удаляет запись структуры с указанным именем из иерархии структуры документа. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert)(int, OutlineItemCollection) | Вставляет элемент схемы в коллекцию в указанном месте. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove#remove_1)(int) | Удалить элемент по индексу. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove#remove)(OutlineItemCollection) | Удалить элемент коллекции контуров. |

### Смотрите также

* class [Outlines](../outlines)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
