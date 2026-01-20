---
title: System::Drawing::Drawing2D::Matrix class
linktitle: Matrix
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::Matrix class. Represents a 3x3 matrix that defines transform operations. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.drawing.drawing2d/matrix/
---
## Matrix class


Represents a 3x3 matrix that defines transform operations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Matrix : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() const | Creates a copy of the current object. |
| [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| [Equals](./equals/)(ptr) override | Tests whether the specified object is a [Matrix](./) and is identical to this object. |
| [get_Elements](./get_elements/)() const | Returns an arry containing the elements of the matrix in the following order: m11, m12, m21, m22, dx, dy. |
| [get_IsIdentity](./get_isidentity/)() const | Determines if the matrix represented by the current object is an identity matrix. |
| [get_IsInvertible](./get_isinvertible/)() const | Determines if the matrix represented by the current object is invertible. |
| [get_OffsetX](./get_offsetx/)() const | Returns the X translation value of the matrix represented by the current object. |
| [get_OffsetY](./get_offsety/)() const | Returns the Y translation value of the matrix represented by the current object. |
| [Invert](./invert/)() | Inverts the matrix represented by the current object. |
| [Matrix](./matrix/)() | Constructs a new instance of [Matrix](./) class that represents an identity matrix. |
| [Matrix](./matrix/)(float, float, float, float, float, float) | Constructs a new instance of [Matrix](./) class and initializes it with the specified values. |
| [Matrix](./matrix/)(const Rectangle\&, const ArrayPtr\<Point\>\&) | Constructs a new instance of the [Matrix](./) class to the geometric transform defined by the specified rectangle and array of points. |
| [Matrix](./matrix/)(const RectangleF\&, const ArrayPtr\<PointF\>\&) | Constructs a new instance of the [Matrix](./) class to the geometric transform defined by the specified rectangle and array of points. |
| [Multiply](./multiply/)(const SharedPtr\<Matrix\>\&) | Multiplies the matrix represented by the current object by the specified matrix. |
| [Multiply](./multiply/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Multiplies the matrix represented by the current object by the specified matrix. |
| [Reset](./reset/)() | Resets the matrix represented by the current object so that it becomes an identity matrix. |
| [Rotate](./rotate/)(float) | Rotates the matrix represented by the current object clockwise by the specified angle. |
| [Rotate](./rotate/)(float, MatrixOrder) | Rotates the matrix represented by the current object clockwise around the origin by the specified angle. |
| [RotateAt](./rotateat/)(float, const PointF\&) | Rotates the matrix represented by the current object clockwise around the specified point by the specified angle. |
| [RotateAt](./rotateat/)(float, const PointF\&, MatrixOrder) | Rotates the matrix represented by the current object clockwise around the specified point by the specified angle. |
| [Scale](./scale/)(float, float) | Applies the specified scale vector to the matrix represented by the current object. |
| [Scale](./scale/)(float, float, MatrixOrder) | Applies the specified scale vector to the matrix represented by the current object. |
| [Shear](./shear/)(float, float) | Applies the specified shear vector to the matrix represented by the current object. |
| [Shear](./shear/)(float, float, MatrixOrder) | Applies the specified shear vector to the matrix represented by the current object. |
| [TransformPoints](./transformpoints/)(const ArrayPtr\<Point\>\&) | Applies the geometric transformation defined by the matrix represented by the current object to the specified points. |
| [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<Point\>\&) | Applies the geometric transformation defined by the matrix represented by the current object to the specified points. |
| [TransformPoints](./transformpoints/)(const ArrayPtr\<PointF\>\&) | Applies the geometric transformation defined by the matrix represented by the current object to the specified points. |
| [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<PointF\>\&) | Applies the geometric transformation defined by the matrix represented by the current object to the specified points. |
| [TransformVectors](./transformvectors/)(const ArrayPtr\<Point\>\&) | Applies only the scale and rotate components of the matrix represented by the current object to the specified points. |
| [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<Point\>\&) | Applies only the scale and rotate components of the matrix represented by the current object to the specified points. |
| [TransformVectors](./transformvectors/)(const ArrayPtr\<PointF\>\&) | Applies only the scale and rotate components of the matrix represented by the current object to the specified points. |
| [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<PointF\>\&) | Applies only the scale and rotate components of the matrix represented by the current object to the specified points. |
| [Translate](./translate/)(float, float) | Applies the specified translate vector to the matrix represented by the current object. |
| [Translate](./translate/)(float, float, MatrixOrder) | Applies the specified translate vector to the matrix represented by the current object. |
| [VectorTransformPoints](./vectortransformpoints/)(const ArrayPtr\<Point\>\&) | Multiplies each vector in an array by the matrix represented by the current object. |
| [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<Point\>\&) | Multiplies each vector in an array by the matrix represented by the current object. |
| virtual [~Matrix](./~matrix/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
