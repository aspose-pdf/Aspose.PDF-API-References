---
title: System::Drawing::Drawing2D::PathGradientBrush class
linktitle: PathGradientBrush
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::PathGradientBrush class. Represents a brush that fills the interior of a GraphicsPath object with a gradient. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1200
url: /cpp/system.drawing.drawing2d/pathgradientbrush/
---
## PathGradientBrush class


Represents a brush that fills the interior of a [GraphicsPath](../graphicspath/) object with a gradient. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Creates a copy of the current object. |
| [get_Blend](./get_blend/)() const | NOT IMPLEMENTED. |
| [get_CenterColor](./get_centercolor/)() const | Returns a color that is at the center of the path filled by the current object. |
| [get_CenterPoint](./get_centerpoint/)() const | Gets the center point of the gradient. |
| [get_FocusScales](./get_focusscales/)() const | Gets the focus point for the gradient falloff. |
| [get_InterpolationColors](./get_interpolationcolors/)() const | Returns a value the defines a multicolor linear gradient. |
| [get_Rectangle](./get_rectangle/)() | NOT IMPLEMENTED. |
| [get_SurroundColors](./get_surroundcolors/)() const | Returns colors that correspond to the points in the path this [PathGradientBrush](./) fills. |
| [get_Transform](./get_transform/)() const | Returns a copy of a [Matrix](../matrix/) object that specifies the geometrical transformations for the brush represented by the current object. |
| [get_WrapMode](./get_wrapmode/)() const | Returns the wrap mode. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Multiplies current object's transform matrix by the specified matrix. |
| [PathGradientBrush](./pathgradientbrush/)(const ArrayPtr\<PointF\>\&, WrapMode) | RTTI information. |
| [PathGradientBrush](./pathgradientbrush/)(const ArrayPtr\<Point\>\&, WrapMode) | Constructs a new instance of [PathGradientBrush](./) class. |
| [PathGradientBrush](./pathgradientbrush/)(const SharedPtr\<GraphicsPath\>\&) | Constructs a new instance of [PathGradientBrush](./) class. |
| [ResetTransform](./resettransform/)() | Resets the current object's transform matrix so that it becomes an identity matrix. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Rotates the local geometric transformation by the specified angle in the specified order. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Scales the local geometric transformation by the specified factors in the specified order. |
| [set_Blend](./set_blend/)(const SharedPtr\<Blend\>\&) | Sets a blend that specifies factors and positions of base colors for this brush. |
| [set_CenterColor](./set_centercolor/)(Color) | Sets a color that is at the center of the path filled by the current object. |
| [set_CenterPoint](./set_centerpoint/)(const PointF\&) | Sets the center point of the gradient. |
| [set_FocusScales](./set_focusscales/)(const PointF\&) | Sets the focus point for the gradient falloff. |
| [set_InterpolationColors](./set_interpolationcolors/)(const SharedPtr\<ColorBlend\>\&) | Sets a value the defines a multicolor linear gradient. |
| [set_SurroundColors](./set_surroundcolors/)(const ArrayPtr\<Color\>\&) | Sets colors that correspond to the points in the path this [PathGradientBrush](./) fills. |
| [set_Transform](./set_transform/)(const SharedPtr\<Matrix\>\&) | Sets a [Matrix](../matrix/) object that specifies the geometrical transformations for the brush represented by the current object. |
| [set_WrapMode](./set_wrapmode/)(WrapMode) | Sets the wrap mode. |
| [SetBlendTriangularShape](./setblendtriangularshape/)(float, float) | NOT IMPLEMENTED. |
| [SetSigmaBellShape](./setsigmabellshape/)(float, float) | NOT IMPLEMENTED. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Translates the local geometric transformation by the specified dimensions in the specified order. |
## See Also

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
