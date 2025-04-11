---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Annotations.XYZExplicitDestination. Представляет явное назначение, которое отображает страницу с координатами (left, top), расположенными в верхнем левом углу окна, и содержимое страницы увеличено в соответствии с коэффициентом zoom. Значение null для любого из параметров left, top или zoom указывает на то, что текущее значение этого параметра должно быть сохранено без изменений. Значение zoom равное 0 имеет то же значение, что и значение null.
type: docs
weight: 2730
url: /ru/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## Класс XYZExplicitDestination

Представляет явное назначение, которое отображает страницу с координатами (left, top), расположенными в верхнем левом углу окна, и содержимое страницы увеличено в соответствии с коэффициентом zoom. Значение null для любого из параметров left, top или zoom указывает на то, что текущее значение этого параметра должно быть сохранено без изменений. Значение zoom равное 0 имеет то же значение, что и значение null.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Создает удаленное явное назначение. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Создает локальное явное назначение. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Получает левую горизонтальную координату верхнего левого угла окна. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Получает объект страницы назначения |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Получает номер страницы назначения |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Получает верхнюю вертикальную координату верхнего левого угла окна. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Получает коэффициент увеличения. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Создает назначение для указанного местоположения страницы с учетом поворота страницы, если это необходимо. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Создает назначение для указанной страницы. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Создает назначение для верхнего левого угла указанной страницы. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Преобразует состояние объекта в строковое значение. Пример: "1 XYZ 100 200 3". |

## Примеры

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### См. также

* класс [ExplicitDestination](../explicitdestination/)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../)