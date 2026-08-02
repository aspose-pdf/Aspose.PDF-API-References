---
title: "Класс OutlineCollection"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.OutlineCollection. Представляет иерархию оглавления документа"
type: docs
weight: 8140
url: /ru/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

Представляет иерархию оглавления document.

```csharp
public sealed class OutlineCollection : Outlines
```

## Свойства

| Имя | Описание |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Количество элементов коллекции. Пожалуйста, не путайте с VisibleCount: VisibleCount возвращает число видимых элементов оглавления на всех уровнях. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Получает элемент оглавления, представляющий первый элемент верхнего уровня в оглавлении. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к этой коллекции (потокобезопасно). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Получает элемент оглавления из коллекции по индексу. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Получает элемент оглавления, представляющий последний элемент верхнего уровня в оглавлении. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Count — это сумма количества видимых дочерних элементов оглавления на всех уровнях. Примечание: пожалуйста, не путайте с Count, который является числом элементов в коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Добавляет элемент оглавления в коллекцию. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Очищает все элементы из коллекции. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Проверяет, содержит ли коллекция данный элемент. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Копирует элементы оглавления в System.Array, начиная с определённого индекса System.Array. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Удаляет все элементы оглавления из оглавления документа. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Удаляет элемент оглавления с указанным заголовком из оглавления документа. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Возвращает перечислитель, который проходит по коллекции. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Удалить элемент по индексу. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Всегда бросает NotImplementedException |

### См. также

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


