---
title: Aspose::Pdf::Matrix3D class
linktitle: Matrix3D
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix3D class. Class represents transformation matrix in C++.'
type: docs
weight: 11000
url: /cpp/aspose.pdf/matrix3d/
---
## Matrix3D class


Class represents transformation matrix.

```cpp
class Matrix3D : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Matrix3D\>) | Adds matrix to other matrix. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Compares matrix against other object. |
| [get_A](./get_a/)() | A member of the transformation matrix. |
| [get_B](./get_b/)() | B member of the transformation matrix. |
| [get_C](./get_c/)() | C member of the transformation matrix. |
| [get_D](./get_d/)() | D member of the transformation matrix. |
| [get_E](./get_e/)() | E member of the transformation matrix. |
| [get_F](./get_f/)() | F member of the transformation matrix. |
| [get_G](./get_g/)() | G member of the transformation matrix. |
| [get_H](./get_h/)() | H member of the transformation matrix. |
| [get_I](./get_i/)() | I member of the transformation matrix. |
| [get_Tx](./get_tx/)() | Tx member of the transformation matrix. |
| [get_Ty](./get_ty/)() | Ty member of the transformation matrix. |
| [get_Tz](./get_tz/)() | Tz member of the transformation matrix. |
| static [GetAngle](./getangle/)(Rotation) | Translates rotation into angle (degrees) |
| [GetHashCode](./gethashcode/)() const override | Hash-code for object. |
| [Matrix3D](./matrix3d/)() | Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]. |
| [Matrix3D](./matrix3d/)(System::ArrayPtr\<double\>) | Constructor accepts a matrix with following array representation: [ A B C D E F G H I Tx Ty Tz]. |
| [Matrix3D](./matrix3d/)(System::SharedPtr\<Matrix3D\>) | Constructor accepts a matrix to create a copy. |
| [Matrix3D](./matrix3d/)(double, double, double, double, double, double, double, double, double, double, double, double) | Initializes transformation matrix with specified coefficients. |
| [set_A](./set_a/)(double) | A member of the transformation matrix. |
| [set_B](./set_b/)(double) | B member of the transformation matrix. |
| [set_C](./set_c/)(double) | C member of the transformation matrix. |
| [set_D](./set_d/)(double) | D member of the transformation matrix. |
| [set_E](./set_e/)(double) | E member of the transformation matrix. |
| [set_F](./set_f/)(double) | F member of the transformation matrix. |
| [set_G](./set_g/)(double) | G member of the transformation matrix. |
| [set_H](./set_h/)(double) | H member of the transformation matrix. |
| [set_I](./set_i/)(double) | I member of the transformation matrix. |
| [set_Tx](./set_tx/)(double) | Tx member of the transformation matrix. |
| [set_Ty](./set_ty/)(double) | Ty member of the transformation matrix. |
| [set_Tz](./set_tz/)(double) | Tz member of the transformation matrix. |
| [ToString](./tostring/)() const override | Returns text representation of the matrix. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
