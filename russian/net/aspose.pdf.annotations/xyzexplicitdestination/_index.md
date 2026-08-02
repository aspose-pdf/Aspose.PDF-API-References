---
title: "Класс XYZExplicitDestination"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Annotations.XYZExplicitDestination. Представляет явное назначение, которое отображает страницу с координатами left top, расположенными в левом верхнем углу окна, и содержимое страницы увеличивается в соответствии с коэффициентом zoom. Значение null для любого из параметров left, top или zoom указывает, что текущие значения этих параметров должны оставаться без изменений. Значение zoom, равное 0, имеет то же значение, что и null."
type: docs
weight: 2830
url: /ru/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class

Представляет явный пункт назначения, который отображает страницу с координатами (left, top), расположенными в левом верхнем углу окна, и содержимое страницы увеличивается в факторе zoom. Значение null для любого из параметров left, top или zoom указывает, что текущее значение этого параметра должно оставаться без изменений. Значение zoom, равное 0, имеет то же значение, что и значение null.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Создаёт удалённый явный пункт назначения. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Создаёт локальный явный пункт назначения. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Получает горизонтальную координату left верхнего левого угла окна. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Получает объект целевой страницы |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Получает номер целевой страницы |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Получает вертикальную координату top верхнего левого угла окна. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Получает коэффициент zoom. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Создайте назначение в указанное место страницы, учитывая поворот страницы, если требуется. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Создайте назначение на указанную страницу. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Создайте назначение в левый верхний угол указанной страницы. |
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

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


