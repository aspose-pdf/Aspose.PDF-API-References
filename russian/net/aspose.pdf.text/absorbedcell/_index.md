---
title: Class AbsorbedCell
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.AbsorbedCell. Представляет ячейку таблицы, которая существует на странице
type: docs
weight: 10410
url: /ru/net/aspose.pdf.text/absorbedcell/
---
## Класс AbsorbedCell

Представляет ячейку таблицы, которая существует на странице

```csharp
public class AbsorbedCell : IComparable<AbsorbedCell>, ITableElement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BorderInfo](../../aspose.pdf.text/absorbedcell/borderinfo/) { get; } | Возвращает информацию о границе для ячейки, когда свойство FlowEngine.TableAbsorber.UseFlowEngine установлено в true. |
| [ColSpan](../../aspose.pdf.text/absorbedcell/colspan/) { get; } | Возвращает количество столбцов, которые ячейка должна занимать, когда свойство TableAbsorber.UseFlowEngine установлено в true. |
| [Rectangle](../../aspose.pdf.text/absorbedcell/rectangle/) { get; } | Получает прямоугольник, который описывает положение ячейки на странице |
| [TextFragments](../../aspose.pdf.text/absorbedcell/textfragments/) { get; } | Получает коллекцию [`TextFragment`](../textfragment/) объектов, которые описывают текст, содержащийся в ячейке |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../aspose.pdf.text/absorbedcell/compareto/)(AbsorbedCell) | Сравнивает текущий объект AbsorbedCell с другим объектом AbsorbedCell и возвращает целое число, которое указывает, предшествует ли текущий объект, следует ли за ним или находится на той же позиции в порядке сортировки, что и другой объект. |

### См. также

* интерфейс [ITableElement](../itableelement/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)