---
title: "Aspose::Pdf::Annotations::FitRExplicitDestination class"
linktitle: "FitRExplicitDestination"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::FitRExplicitDestination class. Представляет явный пункт назначения, который отображает страницу с её содержимым, увеличенным настолько, чтобы прямоугольник, заданный координатами left, bottom, right и top, полностью помещался в окно как по горизонтали, так и по вертикали. Если требуемые коэффициенты масштабирования по горизонтали и вертикали различаются, используется меньший из них, при этом прямоугольник центрируется в окне по другой оси. Значение null для любого из параметров может привести к непредсказуемому поведению в C++."
type: docs
weight: 3700
url: /ru/cpp/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class


Представляет явную точку назначения, отображающую страницу с её содержимым, увеличенным настолько, чтобы прямоугольник, заданный координатами left, bottom, right и top, полностью помещался в окно как по горизонтали, так и по вертикали. Если требуемые коэффициенты масштабирования по горизонтали и вертикали различаются, использовать меньший из них, центрируя прямоугольник в окне по другой оси. Значение null для любого из параметров может привести к непредсказуемому поведению.

```cpp
class FitRExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Методы

| Метод | Описание |
| --- | --- |
| [FitRExplicitDestination](./fitrexplicitdestination/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, double, double, double, double) | Создаёт локальное явное назначение. |
| [FitRExplicitDestination](./fitrexplicitdestination/)(const System::SharedPtr\<Document\>\&, int32_t, double, double, double, double) | Создаёт удалённое явное назначение. |
| [FitRExplicitDestination](./fitrexplicitdestination/)(int32_t, double, double, double, double) | Создаёт удалённое явное назначение. |
| [get_Bottom](./get_bottom/)() | Получает нижнюю вертикальную координату видимого прямоугольника. |
| [get_Left](./get_left/)() | Получает левую горизонтальную координату видимого прямоугольника. |
| [get_Right](./get_right/)() | Получает правую горизонтальную координату видимого прямоугольника. |
| [get_Top](./get_top/)() | Получает верхнюю вертикальную координату видимого прямоугольника. |
| [ToString](./tostring/)() const override | Преобразует состояние объекта в строковое значение. Пример: "1 FitR 100 200 300 400". |
## См. также

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
