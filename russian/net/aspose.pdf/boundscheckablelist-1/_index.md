---
title: Class BoundsCheckableListT
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.BoundsCheckableList1T. Представляет собой обертку BoundsCheckableList вокруг System.Collections.Generic.List
type: docs
weight: 2930
url: /ru/net/aspose.pdf/boundscheckablelist-1/
---
## BoundsCheckableList&lt;T&gt; class

Представляет собой обертку BoundsCheckableList вокруг System.Collections.Generic.List.

```csharp
public class BoundsCheckableList<T> : IList<T>
    where T : IBoundsCheckableItem
```

## Конструкторы

| Name | Description |
| --- | --- |
| [BoundsCheckableList](boundscheckablelist/#constructor)() | Инициализирует новый экземпляр класса BoundsCheckableList. |
| [BoundsCheckableList](boundscheckablelist/#constructor_1)(BoundsCheckMode, double, double) | Инициализирует новый экземпляр класса BoundsCheckableList. |

## Свойства

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf/boundscheckablelist-1/count/) { get; } | Получает количество элементов, содержащихся в System.Collections.Generic.List. |
| [IsReadOnly](../../aspose.pdf/boundscheckablelist-1/isreadonly/) { get; } | Получает значение, указывающее, является ли коллекция только для чтения. |
| [Item](../../aspose.pdf/boundscheckablelist-1/item/) { get; set; } | Получает или устанавливает абзац из коллекции или в коллекцию. |

## Методы

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf/boundscheckablelist-1/add/)(T) | Добавляет объект в конец System.Collections.Generic.List в зависимости от параметра "boundsCheckMode". |
| [Clear](../../aspose.pdf/boundscheckablelist-1/clear/)() | Удаляет все элементы из System.Collections.Generic.List. |
| [Contains](../../aspose.pdf/boundscheckablelist-1/contains/)(T) | Определяет, содержится ли элемент в System.Collections.Generic.List. |
| [CopyTo](../../aspose.pdf/boundscheckablelist-1/copyto/)(T[], int) |  |
| [GetEnumerator](../../aspose.pdf/boundscheckablelist-1/getenumerator/)() | Возвращает перечислитель, который перебирает элементы System.Collections.Generic.List. |
| [IndexOf](../../aspose.pdf/boundscheckablelist-1/indexof/)(T) | Ищет указанный объект и возвращает индекс первого вхождения в пределах всей System.Collections.Generic.List. |
| [Insert](../../aspose.pdf/boundscheckablelist-1/insert/)(int, T) | Вставляет элемент в System.Collections.Generic.List по указанному индексу. |
| [Remove](../../aspose.pdf/boundscheckablelist-1/remove/)(T) | Удаляет первое вхождение конкретного объекта из System.Collections.Generic.List. |
| [RemoveAt](../../aspose.pdf/boundscheckablelist-1/removeat/)(int) | Удаляет элемент по указанному индексу из System.Collections.Generic.List. |
| [UpdateBoundsCheckMode](../../aspose.pdf/boundscheckablelist-1/updateboundscheckmode/#updateboundscheckmode)(BoundsCheckMode) | Обновляет параметр boundsCheckMode для инициализированной коллекции. |
| [UpdateBoundsCheckMode](../../aspose.pdf/boundscheckablelist-1/updateboundscheckmode/#updateboundscheckmode_1)(BoundsCheckMode, double, double) | Обновляет параметр boundsCheckMode для инициализированной коллекции. |

### См. также

* интерфейс [IBoundsCheckableItem](../iboundscheckableitem/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)