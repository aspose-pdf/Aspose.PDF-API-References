---
title: "Aspose::Pdf::Annotations::Measure класс"
linktitle: "Measure"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::Measure класс. Класс, описывающий систему координат Measure в C++."
type: docs
weight: 6200
url: /ru/cpp/aspose.pdf.annotations/measure/
---
## Measure class


Класс, описывающий координатную систему [Measure](./).

```cpp
class Measure : public System::Object
```

## Nested classes

* Class [NumberFormat](./numberformat/)
* Class [NumberFormatList](./numberformatlist/)
## Методы

| Метод | Описание |
| --- | --- |
| [get_AngleFormat](./get_angleformat/)() | Массив форматов чисел для измерения углов. |
| [get_AreaFormat](./get_areaformat/)() | Массив форматов чисел для измерения площади. |
| [get_DistanceFormat](./get_distanceformat/)() | Массив форматов чисел для измерения расстояния в любом направлении. |
| [get_Origin](./get_origin/)() | [Point](../../aspose.pdf/point/) который указывает начало координат измерительной системы в координатах пространства пользователя по умолчанию. |
| [get_ScaleRatio](./get_scaleratio/)() | Текстовая строка, выражающая масштабное соотношение чертежа. |
| [get_SlopeFormat](./get_slopeformat/)() | Массив форматов чисел для измерения наклона линии. |
| [get_XFormat](./get_xformat/)() | Массив форматов чисел для измерения изменения вдоль оси x и, если Y отсутствует, также вдоль оси y. |
| [get_XYFactor](./get_xyfactor/)() | Коэффициент, который будет использоваться для преобразования наибольших единиц вдоль оси y в наибольшие единицы вдоль оси x. |
| [get_YFormat](./get_yformat/)() | Массив форматов чисел для измерения изменения вдоль оси y. |
| [Measure](./measure/)(const System::SharedPtr\<Annotation\>\&) | Создаёт объект [Measure](./) для аннотаций измерения. |
| [set_AngleFormat](./set_angleformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Массив форматов чисел для измерения углов. |
| [set_AreaFormat](./set_areaformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Массив форматов чисел для измерения площади. |
| [set_DistanceFormat](./set_distanceformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Массив форматов чисел для измерения расстояния в любом направлении. |
| [set_Origin](./set_origin/)(const System::SharedPtr\<Point\>\&) | [Point](../../aspose.pdf/point/) который указывает начало координат измерительной системы в координатах пространства пользователя по умолчанию. |
| [set_ScaleRatio](./set_scaleratio/)(const System::String\&) | Текстовая строка, выражающая масштабное соотношение чертежа. |
| [set_SlopeFormat](./set_slopeformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Массив форматов чисел для измерения наклона линии. |
| [set_XFormat](./set_xformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Массив форматов чисел для измерения изменения вдоль оси x и, если Y отсутствует, также вдоль оси y. |
| [set_XYFactor](./set_xyfactor/)(double) | Коэффициент, который будет использоваться для преобразования наибольших единиц вдоль оси y в наибольшие единицы вдоль оси x. |
| [set_YFormat](./set_yformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Массив форматов чисел для измерения изменения вдоль оси y. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
