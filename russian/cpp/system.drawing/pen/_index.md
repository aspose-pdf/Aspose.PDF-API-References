---
title: "System::Drawing::Pen class"
linktitle: "Pen"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Pen class. Представляет свойства, такие как цвет, ширина и т.п., линий и кривых, которые рисуются. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1500
url: /ru/cpp/system.drawing/pen/
---
## Pen class


Представляет свойства, такие как цвет, ширина и т.п., линий и кривых, которые рисуются. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Pen : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() | Возвращает копию текущего объекта. |
| [Dispose](./dispose/)() | Освобождает все операционные ресурсы, полученные текущим объектом. |
| [get_Alignment](./get_alignment/)() const | Возвращает значение, указывающее выравнивание текущего объекта [Pen](./). |
| [get_Brush](./get_brush/)() | Возвращает объект [Brush](../brush/) этой ручки. |
| [get_Color](./get_color/)() const | Возвращает цвет этой ручки. |
| [get_CompoundArray](./get_compoundarray/)() const | Возвращает массив значений, определяющих составную ручку. |
| [get_DashCap](./get_dashcap/)() const | Возвращает значение, указывающее тип заглавия, используемого на обоих концах пунктирной линии. |
| [get_DashOffset](./get_dashoffset/)() const | Возвращает расстояние от начала линии до начала шаблона пунктиров. |
| [get_DashPattern](./get_dashpattern/)() const | Возвращает массив, указывающий пользовательский шаблон пунктиров в пунктирной линии. |
| [get_DashStyle](./get_dashstyle/)() const | Возвращает значение, указывающее стиль пунктиров текущего объекта [Pen](./). |
| [get_EndCap](./get_endcap/)() const | Возвращает значение, указывающее конечное закругление линии текущего объекта [Pen](./). |
| [get_LineJoin](./get_linejoin/)() const | Возвращает значение, указывающее, как соединяются линии, нарисованные этим объектом [Pen](./). |
| [get_MiterLimit](./get_miterlimit/)() const | Возвращает предел толщины соединения на скошенном угле. |
| [get_PenType](./get_pentype/)() const | НЕ РЕАЛИЗОВАНО. |
| [get_StartCap](./get_startcap/)() const | Возвращает значение, указывающее начальное закругление линии текущего объекта [Pen](./). |
| [get_Transform](./get_transform/)() | Возвращает копию объекта Matrix, который задает геометрические преобразования для ручки, представленной текущим объектом. |
| [get_Width](./get_width/)() const | Возвращает ширину текущего объекта [Pen](./). |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) | Умножает матрицу преобразования текущего объекта на указанную матрицу. |
| [Pen](./pen/)(const Color\&) | Создаёт новый объект [Pen](./), представляющий указанный цвет. |
| [Pen](./pen/)(const Color\&, float) | Создаёт новый объект [Pen](./), представляющий указанный цвет и ширину. |
| [Pen](./pen/)(const SharedPtr\<Brush\>\&) | Создаёт новый объект [Pen](./) и инициализирует его указанным объектом [Brush](../brush/). |
| [Pen](./pen/)(const SharedPtr\<Brush\>\&, float) | Создаёт новый объект [Pen](./) и инициализирует его указанным объектом [Brush](../brush/). |
| [ResetTransform](./resettransform/)() | Сбрасывает матрицу преобразования текущего объекта, делая её единичной матрицей. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Вращает локальное геометрическое преобразование на указанный угол в указанном порядке. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке. |
| [set_Alignment](./set_alignment/)(Drawing2D::PenAlignment) | Устанавливает выравнивание текущего объекта [Pen](./). |
| [set_Brush](./set_brush/)(const SharedPtr\<Brush\>\&) | Устанавливает объект [Brush](../brush/) этой ручки. |
| [set_Color](./set_color/)(const Color\&) | Устанавливает цвет этой ручки. |
| [set_CompoundArray](./set_compoundarray/)(const System::ArrayPtr\<float\>\&) | Устанавливает массив значений, определяющих составную ручку. |
| [set_CustomEndCap](./set_customendcap/)(const SharedPtr\<Drawing2D::CustomLineCap\>\&) | Устанавливает пользовательское конечное закругление линии. |
| [set_CustomStartCap](./set_customstartcap/)(const SharedPtr\<Drawing2D::CustomLineCap\>\&) | Устанавливает пользовательское начальное закругление линии. |
| [set_DashCap](./set_dashcap/)(Drawing2D::DashCap) | Устанавливает значение, определяющее тип заглавия, используемого на обоих концах пунктирной линии. |
| [set_DashOffset](./set_dashoffset/)(float) | Устанавливает расстояние от начала линии до начала шаблона пунктиров. |
| [set_DashPattern](./set_dashpattern/)(const System::ArrayPtr\<float\>\&) | Устанавливает массив, задающий пользовательский шаблон пунктиров в пунктирной линии. Массив состоит из чисел, определяющих длину чередующихся пунктиров и пробелов. |
| [set_DashStyle](./set_dashstyle/)(Drawing2D::DashStyle) | Устанавливает значение, определяющее стиль пунктиров текущего объекта [Pen](./). |
| [set_EndCap](./set_endcap/)(Drawing2D::LineCap) | Устанавливает конечную форму линии текущего объекта [Pen](./). |
| [set_LineJoin](./set_linejoin/)(Drawing2D::LineJoin) | Устанавливает значение, определяющее, как соединяются линии, нарисованные этим объектом [Pen](./). |
| [set_MiterLimit](./set_miterlimit/)(float) | Устанавливает ограничение толщины соединения на скошенном углу. |
| [set_StartCap](./set_startcap/)(Drawing2D::LineCap) | Устанавливает начальную форму линии текущего объекта [Pen](./). |
| [set_Transform](./set_transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Устанавливает объект Matrix, который определяет геометрические преобразования для пера, представленного текущим объектом. |
| [set_Width](./set_width/)(float) | Устанавливает ширину текущего объекта [Pen](./). |
| [SetLineCap](./setlinecap/)(Drawing2D::LineCap, Drawing2D::LineCap, Drawing2D::DashCap) | НЕ РЕАЛИЗОВАНО. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
