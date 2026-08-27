---
title: "Класс OutlineItemCollection"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.OutlineItemCollection класс. Представляет запись оглавления в иерархии оглавления PDF‑документа"
type: docs
weight: 8150
url: /ru/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

Представляет запись оглавления в иерархии оглавления PDF document.

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
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Получает или задаёт действие для этого элемента оглавления. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Получает или задаёт флаг полужирного начертания для текста заголовка этого элемента оглавления |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Получает или задаёт цвет текста заголовка этого элемента оглавления. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Количество элементов коллекции. Пожалуйста, не путайте с VisibleCount: VisibleCount возвращает число видимых элементов оглавления на всех уровнях. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Получает или задаёт назначение для этого элемента оглавления. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Получает элемент оглавления, представляющий первый элемент верхнего уровня в иерархии оглавления. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Проверьте, представляет ли элемент оглавления следующий элемент относительно данного элемента в иерархии оглавления. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к этой коллекции (потокобезопасен). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Получает или задаёт флаг курсивного начертания для текста заголовка этого элемента оглавления |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | Получает элемент оглавления из коллекции по индексу. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Получает элемент оглавления, представляющий последний элемент верхнего уровня в иерархии оглавления. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Получает уровень иерархии элемента оглавления. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Получает элемент оглавления, представляющий следующий элемент относительно данного элемента в иерархии оглавления. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Получает или задает статус открытости (true/false) для пункта оглавления. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Получает родительский объект этого пункта оглавления в иерархии оглавления. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Получает пункт оглавления, представляющий предыдущий пункт относительно этого пункта в иерархии оглавления. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Получает объект, который может использоваться для синхронизации доступа к этой коллекции. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Получает или задает заголовок для этого пункта оглавления. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Получает общее количество пунктов оглавления на всех уровнях в иерархии оглавления документа. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Добавляет элемент оглавления в коллекцию. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Очищает все элементы из коллекции. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Проверяет, содержит ли коллекция заданный элемент. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Копирует записи оглавления в System.Array, начиная с указанного индекса System.Array. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Удаляет этот пункт оглавления из иерархии оглавления документа. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Удаляет запись оглавления с указанным именем из иерархии оглавления документа. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Возвращает перечислитель, который проходит по коллекции. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Вставляет пункт оглавления в коллекцию в указанное место. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | Удалить элемент по индексу. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Удаляет элемент коллекции оглавления. |

### См. также

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


