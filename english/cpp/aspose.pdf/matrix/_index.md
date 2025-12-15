---
title: Aspose::Pdf::Matrix class
linktitle: Matrix
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix class. Class represents transformation matrix in C++.'
type: docs
weight: 11100
url: /cpp/aspose.pdf/matrix/
---
## Matrix class


Class represents transformation matrix.

```cpp
class Matrix : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Matrix\>) | Adds matrix to other matrix. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Compares matrix agains other object. |
| [get_A](./get_a/)() | A member of the transformation matrix. |
| [get_B](./get_b/)() | B member of the transformation matrix. |
| [get_C](./get_c/)() | C member of the transformation matrix. |
| [get_D](./get_d/)() | D member of the transformation matrix. |
| [get_Data](./get_data/)() const | Gets data of [Matrix](./) as array. |
| [get_E](./get_e/)() | E member of the transformation matrix. |
| [get_Elements](./get_elements/)() | Elements of the matrix. |
| [get_F](./get_f/)() | F member of the transformation matrix. |
| static [GetAngle](./getangle/)(Aspose::Pdf::Rotation) | Transaltes rotation into angle (degrees) |
| [GetFlipMatrix](./getflipmatrix/)() | Gets the flipping matrix. |
| [GetHashCode](./gethashcode/)() const override | Hash-code for object. |
| [Matrix](./matrix/)() | Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]. |
| [Matrix](./matrix/)(System::ArrayPtr\<double\>) | Constructor accepts a matrix with following array representation: [ A B C D E F ]. |
| [Matrix](./matrix/)(const System::Details::ArrayView\<float\>\&) | Constructor accepts a matrix with following array representation: [ A B C D E F ]. |
| [Matrix](./matrix/)(System::SharedPtr\<Matrix\>) | Constructor accepts a matrix to create a copy. |
| [Matrix](./matrix/)(double, double, double, double, double, double) | Initializes transformation matrix with specified coefficients. |
| [Multiply](./multiply/)(System::SharedPtr\<Matrix\>) | Multiplies the matrix by other matrix. |
| [Reverse](./reverse/)() | Calculates reverse matrix. |
| static [Rotation](./rotation/)(double) | Creates matrix for given rotation angle. |
| static [Rotation](./rotation/)(Aspose::Pdf::Rotation) | Creates matrix for given rotation. |
| [Scale](./scale/)(double, double, double\&, double\&) | Scales x and y with the matrix using the following formula: x1 = A*x + C*y; y1 = B*x + D*y;. |
| static [Scale](./scale/)(double, double, System::SharedPtr\<Matrix\>) | Applies scaling to the given matrix. |
| [set_A](./set_a/)(double) | A member of the transformation matrix. |
| [set_B](./set_b/)(double) | B member of the transformation matrix. |
| [set_C](./set_c/)(double) | C member of the transformation matrix. |
| [set_D](./set_d/)(double) | D member of the transformation matrix. |
| [set_E](./set_e/)(double) | E member of the transformation matrix. |
| [set_F](./set_f/)(double) | F member of the transformation matrix. |
| static [Skew](./skew/)(double, double) | Creates matrix for given rotation angle. |
| [ToString](./tostring/)() const override | Returns text reporesentation of the matrix. |
| [Transform](./transform/)(System::SharedPtr\<Point\>) | Transforms point using this matrix. |
| [Transform](./transform/)(double, double, double\&, double\&) | Transforms coordinates using this matrix. |
| [Transform](./transform/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Transformes rectangle. If angle is not 90 * N degrees then bounding rectangle is returned. |
| static [Translate](./translate/)(double, double, System::SharedPtr\<Matrix\>) | Translates a matrix by the specified amount in the x and y direction. |
| [UnScale](./unscale/)(double, double, double\&, double\&) | Scales back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);. |
| [UnTransform](./untransform/)(double, double, double\&, double\&) | Transforms back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
