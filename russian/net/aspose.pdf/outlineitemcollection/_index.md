---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.OutlineItemCollection. Представляет элемент оглавления в иерархии оглавления PDF-документа
type: docs
weight: 8010
url: /ru/net/aspose.pdf/outlineitemcollection/
---
## Класс OutlineItemCollection

Представляет элемент оглавления в иерархии оглавления PDF-документа.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | Инициализирует экземпляр элемента оглавления, используя объект корневой иерархии. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Получает или задает действие для этого элемента оглавления. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Получает или задает флаг жирного шрифта для текста заголовка этого элемента оглавления |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Получает или задает цвет для текста заголовка этого элемента оглавления. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Количество элементов в коллекции. Пожалуйста, не путайте с VisibleCount: VisibleCount получает количество видимых элементов оглавления на всех уровнях. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Получает или задает назначение для этого элемента оглавления. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Получает элемент оглавления, представляющий первый элемент верхнего уровня в иерархии оглавления. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Проверяет, представляет ли элемент оглавления следующий элемент относительно этого элемента в иерархии оглавления. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Получает значение, указывающее, является ли коллекция только для чтения. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к этой коллекции (безопасно для потоков). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Получает или задает флаг курсивного шрифта для текста заголовка этого элемента оглавления |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | Получает элемент оглавления из коллекции по индексу. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Получает элемент оглавления, представляющий последний элемент верхнего уровня в иерархии оглавления. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Получает уровень иерархии элемента оглавления. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Получает элемент оглавления, представляющий следующий элемент относительно этого элемента в иерархии оглавления. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Получает или задает статус открытия (true/false) для элемента оглавления. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Получает родительский объект этого элемента оглавления в иерархии оглавления. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Получает элемент оглавления, представляющий предыдущий элемент относительно этого элемента в иерархии оглавления. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Получает или задает заголовок для этого элемента оглавления. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Получает общее количество элементов оглавления на всех уровнях в иерархии оглавления документа. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Добавляет элемент оглавления в коллекцию. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Очищает все элементы из коллекции. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Проверяет, содержит ли коллекция данный элемент. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Копирует элементы оглавления в массив System.Array, начиная с определенного индекса массива System.Array. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Удаляет этот элемент оглавления из иерархии оглавления документа. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Удаляет элемент оглавления с указанным именем из иерархии оглавления документа. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Возвращает перечислитель, который перебирает коллекцию. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Вставляет элемент оглавления в коллекцию в указанном месте. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | Удаляет элемент по индексу. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Удаляет элемент коллекции оглавления. |

### См. также

* класс [Outlines](../outlines/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)