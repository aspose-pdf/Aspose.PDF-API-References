---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.OutlineCollection. Представляет иерархию оглавления документа
type: docs
weight: 8000
url: /ru/net/aspose.pdf/outlinecollection/
---
## Класс OutlineCollection

Представляет иерархию оглавления документа.

```csharp
public sealed class OutlineCollection : Outlines
```

## Свойства

| Имя | Описание |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Количество элементов в коллекции. Пожалуйста, не путайте с VisibleCount: VisibleCount получает количество видимых элементов оглавления на всех уровнях. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Получает элемент оглавления, представляющий первый элемент верхнего уровня в оглавлении. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Получает значение, указывающее, является ли коллекция только для чтения. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к этой коллекции (безопасно для потоков). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Получает элемент оглавления из коллекции по индексу. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Получает элемент оглавления, представляющий последний элемент верхнего уровня в оглавлении. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Количество — это сумма количества видимых дочерних элементов оглавления на всех уровнях. Примечание: пожалуйста, не путайте с Count, который является количеством элементов в коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Добавляет элемент оглавления в коллекцию. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Очищает все элементы из коллекции. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Проверяет, содержит ли коллекция данный элемент. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Копирует элементы оглавления в System.Array, начиная с определенного индекса System.Array. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Удаляет все элементы оглавления из оглавления документа. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Удаляет элемент оглавления с указанным заголовком из оглавления документа. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Возвращает перечислитель, который перебирает коллекцию. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Удаляет элемент по индексу. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Всегда вызывает NotImplementedException |

### См. также

* класс [Outlines](../outlines/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)