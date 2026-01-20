---
title: System::Drawing::Drawing2D::LinearGradientBrush class
linktitle: LinearGradientBrush
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::LinearGradientBrush class. Represents a linear gradient brush. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.drawing.drawing2d/lineargradientbrush/
---
## LinearGradientBrush class


Represents a linear gradient brush. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class LinearGradientBrush : public System::Drawing::Brush
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Creates a copy of the current object. |
| [get_Blend](./get_blend/)() const | Returns a blend that specifies factors and positions of base colors for this brush. |
| [get_GammaCorrection](./get_gammacorrection/)() const | Returns a value indicating that gamma correction is enabled for this brush. |
| [get_InterpolationColors](./get_interpolationcolors/)() const | Returns a [ColorBlend](../colorblend/) object that defines a multicolor linear gradient. |
| [get_LinearColors](./get_linearcolors/)() const | Returns starting and ending colors of this gradient. |
| [get_Rectangle](./get_rectangle/)() | Returns a bounding rectangle. |
| [get_Transform](./get_transform/)() const | Returns a copy of a [Matrix](../matrix/) object that specifies the geometrical transformations for the brush represented by the current object. |
| [get_WrapMode](./get_wrapmode/)() const | Returns the wrap mode. |
| [LinearGradientBrush](./lineargradientbrush/)(const PointF\&, const PointF\&, const Color\&, const Color\&) | RTTI information. |
| [LinearGradientBrush](./lineargradientbrush/)(const Point\&, const Point\&, const Color\&, const Color\&) | Constructs a new instance of [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const RectangleF\&, const Color\&, const Color\&, LinearGradientMode) | Constructs a new instance of [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const Rectangle\&, const Color\&, const Color\&, LinearGradientMode) | Constructs a new instance of [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const RectangleF\&, const Color\&, const Color\&, float, bool) | Constructs a new instance of [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const Rectangle\&, const Color\&, const Color\&, float, bool) | Constructs a new instance of [LinearGradientBrush](./). |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Multiplies current object's transform matrix by the specified matrix. |
| [ResetTransform](./resettransform/)() | Resets current object's transformation matrix. |
| [RotateTransform](./rotatetransform/)(float, MatrixOrder) | Rotates current object's transform matrix. |
| [ScaleTransform](./scaletransform/)(float, float, MatrixOrder) | Scales current object's transform matrix. |
| [set_Blend](./set_blend/)(const SharedPtr\<Blend\>\&) | Sets a blend that specifies factors and positions of base colors for this brush. |
| [set_GammaCorrection](./set_gammacorrection/)(bool) | Sets gamma correction status for this brush. |
| [set_InterpolationColors](./set_interpolationcolors/)(const SharedPtr\<ColorBlend\>\&) | Sets a [ColorBlend](../colorblend/) object that defines a multicolor linear gradient. |
| [set_LinearColors](./set_linearcolors/)(const ArrayPtr\<Color\>\&) | Sets starting and ending colors of this gradient. |
| [set_Transform](./set_transform/)(const SharedPtr\<Matrix\>\&) | Sets a [Matrix](../matrix/) object that specifies the geometrical transformations for the brush represented by the current object. |
| [set_WrapMode](./set_wrapmode/)(WrapMode) | Sets the wrap mode. |
| [SetBlendTriangularShape](./setblendtriangularshape/)(float, float) | NOT IMPLEMENTED. |
| [SetSigmaBellShape](./setsigmabellshape/)(float, float) | NOT IMPLEMENTED. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Translates current object's transform matrix. |
## See Also

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
