---
title: "Класс System::Drawing::Drawing2D::PathGradientBrush"
linktitle: "PathGradientBrush"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Drawing::Drawing2D::PathGradientBrush. Представляет кисть, заполняющую внутреннюю часть объекта GraphicsPath градиентом. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1200
url: /ru/cpp/system.drawing.drawing2d/pathgradientbrush/
---
## PathGradientBrush class


Представляет кисть, заполняющую внутреннюю часть объекта [GraphicsPath](../graphicspath/) градиентом. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Создаёт копию текущего объекта. |
| [get_Blend](./get_blend/)() const | НЕ РЕАЛИЗОВАНО. |
| [get_CenterColor](./get_centercolor/)() const | Возвращает цвет, находящийся в центре пути, заполненного текущим объектом. |
| [get_CenterPoint](./get_centerpoint/)() const | Получает центральную точку градиента. |
| [get_FocusScales](./get_focusscales/)() const | Получает точку фокуса падения градиента. |
| [get_InterpolationColors](./get_interpolationcolors/)() const | Возвращает значение, определяющее многокрасный линейный градиент. |
| [get_Rectangle](./get_rectangle/)() | НЕ РЕАЛИЗОВАНО. |
| [get_SurroundColors](./get_surroundcolors/)() const | Возвращает цвета, соответствующие точкам в пути, который заполняет этот [PathGradientBrush](./). |
| [get_Transform](./get_transform/)() const | Возвращает копию объекта [Matrix](../matrix/), определяющего геометрические преобразования для кисти, представленной текущим объектом. |
| [get_WrapMode](./get_wrapmode/)() const | Возвращает режим обёртки. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Умножает матрицу преобразования текущего объекта на указанную матрицу. |
| [PathGradientBrush](./pathgradientbrush/)(const ArrayPtr\<PointF\>\&, WrapMode) | Информация RTTI. |
| [PathGradientBrush](./pathgradientbrush/)(const ArrayPtr\<Point\>\&, WrapMode) | Создаёт новый экземпляр класса [PathGradientBrush](./). |
| [PathGradientBrush](./pathgradientbrush/)(const SharedPtr\<GraphicsPath\>\&) | Создаёт новый экземпляр класса [PathGradientBrush](./). |
| [ResetTransform](./resettransform/)() | Сбрасывает матрицу преобразования текущего объекта, делая её единичной матрицей. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Вращает локальное геометрическое преобразование на указанный угол в указанном порядке. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке. |
| [set_Blend](./set_blend/)(const SharedPtr\<Blend\>\&) | Устанавливает смесь, задающую коэффициенты и позиции базовых цветов для этой кисти. |
| [set_CenterColor](./set_centercolor/)(Color) | Устанавливает цвет, находящийся в центре пути, заполненного текущим объектом. |
| [set_CenterPoint](./set_centerpoint/)(const PointF\&) | Устанавливает центральную точку градиента. |
| [set_FocusScales](./set_focusscales/)(const PointF\&) | Устанавливает точку фокуса для затухания градиента. |
| [set_InterpolationColors](./set_interpolationcolors/)(const SharedPtr\<ColorBlend\>\&) | Устанавливает значение, определяющее многоцветный линейный градиент. |
| [set_SurroundColors](./set_surroundcolors/)(const ArrayPtr\<Color\>\&) | Устанавливает цвета, соответствующие точкам в пути, который заполняет этот [PathGradientBrush](./). |
| [set_Transform](./set_transform/)(const SharedPtr\<Matrix\>\&) | Устанавливает объект [Matrix](../matrix/), определяющий геометрические преобразования кисти, представленной текущим объектом. |
| [set_WrapMode](./set_wrapmode/)(WrapMode) | Устанавливает режим обтекания. |
| [SetBlendTriangularShape](./setblendtriangularshape/)(float, float) | НЕ РЕАЛИЗОВАНО. |
| [SetSigmaBellShape](./setsigmabellshape/)(float, float) | НЕ РЕАЛИЗОВАНО. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
## См. также

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
