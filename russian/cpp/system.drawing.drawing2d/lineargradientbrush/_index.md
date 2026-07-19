---
title: "Класс System::Drawing::Drawing2D::LinearGradientBrush"
linktitle: "LinearGradientBrush"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Drawing::Drawing2D::LinearGradientBrush. Представляет кисть линейного градиента. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 900
url: /ru/cpp/system.drawing.drawing2d/lineargradientbrush/
---
## LinearGradientBrush class


Представляет кисть линейного градиента. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class LinearGradientBrush : public System::Drawing::Brush
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Создаёт копию текущего объекта. |
| [get_Blend](./get_blend/)() const | Возвращает градиент, определяющий коэффициенты и позиции базовых цветов для этой кисти. |
| [get_GammaCorrection](./get_gammacorrection/)() const | Возвращает значение, указывающее, что гамма‑коррекция включена для этой кисти. |
| [get_InterpolationColors](./get_interpolationcolors/)() const | Возвращает объект [ColorBlend](../colorblend/), определяющий многокрасочный линейный градиент. |
| [get_LinearColors](./get_linearcolors/)() const | Возвращает начальный и конечный цвета этого градиента. |
| [get_Rectangle](./get_rectangle/)() | Возвращает ограничивающий прямоугольник. |
| [get_Transform](./get_transform/)() const | Возвращает копию объекта [Matrix](../matrix/), определяющего геометрические преобразования для кисти, представленной текущим объектом. |
| [get_WrapMode](./get_wrapmode/)() const | Возвращает режим обёртки. |
| [LinearGradientBrush](./lineargradientbrush/)(const PointF\&, const PointF\&, const Color\&, const Color\&) | Информация RTTI. |
| [LinearGradientBrush](./lineargradientbrush/)(const Point\&, const Point\&, const Color\&, const Color\&) | Создает новый экземпляр [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const RectangleF\&, const Color\&, const Color\&, LinearGradientMode) | Создает новый экземпляр [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const Rectangle\&, const Color\&, const Color\&, LinearGradientMode) | Создает новый экземпляр [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const RectangleF\&, const Color\&, const Color\&, float, bool) | Создает новый экземпляр [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const Rectangle\&, const Color\&, const Color\&, float, bool) | Создает новый экземпляр [LinearGradientBrush](./). |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Умножает матрицу преобразования текущего объекта на указанную матрицу. |
| [ResetTransform](./resettransform/)() | Сбрасывает матрицу преобразования текущего объекта. |
| [RotateTransform](./rotatetransform/)(float, MatrixOrder) | Вращает матрицу преобразования текущего объекта. |
| [ScaleTransform](./scaletransform/)(float, float, MatrixOrder) | Масштабирует матрицу преобразования текущего объекта. |
| [set_Blend](./set_blend/)(const SharedPtr\<Blend\>\&) | Устанавливает смесь, задающую коэффициенты и позиции базовых цветов для этой кисти. |
| [set_GammaCorrection](./set_gammacorrection/)(bool) | Устанавливает статус коррекции гаммы для этой кисти. |
| [set_InterpolationColors](./set_interpolationcolors/)(const SharedPtr\<ColorBlend\>\&) | Устанавливает объект [ColorBlend](../colorblend/), определяющий многокрасочный линейный градиент. |
| [set_LinearColors](./set_linearcolors/)(const ArrayPtr\<Color\>\&) | Устанавливает начальный и конечный цвета этого градиента. |
| [set_Transform](./set_transform/)(const SharedPtr\<Matrix\>\&) | Устанавливает объект [Matrix](../matrix/), определяющий геометрические преобразования кисти, представленной текущим объектом. |
| [set_WrapMode](./set_wrapmode/)(WrapMode) | Устанавливает режим обтекания. |
| [SetBlendTriangularShape](./setblendtriangularshape/)(float, float) | НЕ РЕАЛИЗОВАНО. |
| [SetSigmaBellShape](./setsigmabellshape/)(float, float) | НЕ РЕАЛИЗОВАНО. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Перемещает матрицу преобразования текущего объекта. |
## См. также

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
