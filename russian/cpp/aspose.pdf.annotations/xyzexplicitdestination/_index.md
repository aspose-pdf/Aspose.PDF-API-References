---
title: "Aspose::Pdf::Annotations::XYZExplicitDestination класс"
linktitle: "XYZExplicitDestination"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::XYZExplicitDestination класс. Представляет явный пункт назначения, который отображает страницу с координатами (left, top), расположенными в левом верхнем углу окна, и содержимое страницы увеличивается коэффициентом масштабирования. Значение null для любого из параметров left, top или zoom указывает, что текущее значение этого параметра должно оставаться без изменений. Значение масштабирования 0 имеет то же значение, что и значение null в C++."
type: docs
weight: 12000
url: /ru/cpp/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class


Представляет явный пункт назначения, который отображает страницу с координатами (left, top), расположенными в левом верхнем углу окна, и содержимое страницы увеличивается с коэффициентом zoom. Значение null для любого из параметров left, top или zoom указывает, что текущие значения этих параметров должны оставаться без изменений. Значение zoom, равное 0, имеет то же значение, что и null.

```cpp
class XYZExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Методы

| Метод | Описание |
| --- | --- |
| static [CreateDestination](./createdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double, double, double, bool) | Создайте пункт назначения в указанное место страницы, учитывая поворот страницы, если требуется. |
| static [CreateDestinationToUpperLeftCorner](./createdestinationtoupperleftcorner/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double) | Создайте пункт назначения в левый верхний угол указанной страницы. |
| static [CreateDestinationToUpperLeftCorner](./createdestinationtoupperleftcorner/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Создайте пункт назначения на указанную страницу. |
| [get_Left](./get_left/)() | Получает горизонтальную координату left левого верхнего угла окна. |
| [get_Top](./get_top/)() | Получает вертикальную координату top левого верхнего угла окна. |
| [get_Zoom](./get_zoom/)() | Получает коэффициент масштабирования. |
| [ToString](./tostring/)() const override | Преобразует состояние объекта в строковое значение. Пример: "1 XYZ 100 200 3". |
| [XYZExplicitDestination](./xyzexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double, double, double) | Создаёт локальное явное назначение. |
| [XYZExplicitDestination](./xyzexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double, double, double) | Создаёт удалённое явное назначение. |
| [XYZExplicitDestination](./xyzexplicitdestination/)(int32_t, double, double, double) | Создаёт удалённое явное назначение. |
## См. также

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
