---
title: "Класс FitRExplicitDestination"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Annotations.FitRExplicitDestination. Представляет явный пункт назначения, который отображает страницу с её содержимым, увеличенным ровно настолько, чтобы вписать прямоугольник, заданный координатами left, bottom, right и top, полностью в окно как по горизонтали, так и по вертикали. Если требуемые коэффициенты масштабирования по горизонтали и вертикали различаются, использовать меньший из двух, центрируя прямоугольник в окне по другой оси. Значение null для любого из параметров может привести к непредсказуемому поведению."
type: docs
weight: 1870
url: /ru/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class

Представляет явное назначение, которое отображает страницу с её содержимым, увеличенным настолько, чтобы прямоугольник, указанный координатами left, bottom, right и top, полностью помещался в окно как по горизонтали, так и по вертикали. Если требуемые коэффициенты масштабирования по горизонтали и вертикали различаются, использовать меньший из них, центрируя прямоугольник в окне по другой оси. Значение null для любого из параметров может привести к непредсказуемому поведению.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | Создаёт удалённый явный пункт назначения. |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | Создаёт локальный явный пункт назначения. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | Получает нижнюю вертикальную координату видимого прямоугольника. |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | Получает левую горизонтальную координату видимого прямоугольника. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Получает объект целевой страницы |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Получает номер целевой страницы |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | Получает правую горизонтальную координату видимого прямоугольника. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | Получает верхнюю вертикальную координату видимого прямоугольника. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | Преобразует состояние объекта в строковое значение. Пример: "1 FitR 100 200 300 400". |

### См. также

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


