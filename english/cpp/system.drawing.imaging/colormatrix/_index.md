---
title: System::Drawing::Imaging::ColorMatrix class
linktitle: ColorMatrix
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::ColorMatrix class. Represents a 5x5 matrix that contains the coordinates for the RGBAW color space. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.drawing.imaging/colormatrix/
---
## ColorMatrix class


Represents a 5x5 matrix that contains the coordinates for the RGBAW color space. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ColorMatrix : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [ColorMatrix](./colormatrix/)() | Constructs a new instance of [ColorMatrix](./) class and initializes it with the values of identity matrix. |
| [ColorMatrix](./colormatrix/)(const System::ArrayPtr\<System::ArrayPtr\<float\>\>\&) | Constructs a new instance of [ColorMatrix](./) class and initializes it with the specified values. |
| [get_Matrix00](./get_matrix00/)() const | Returns a value in 0-th row and 0-th column. |
| [get_Matrix01](./get_matrix01/)() const | Returns a value in 0-th row and 1-st column. |
| [get_Matrix02](./get_matrix02/)() const | Returns a value in 0-th row and 2-nd column. |
| [get_Matrix03](./get_matrix03/)() const | Returns a value in 0-th row and 3-rd column. |
| [get_Matrix04](./get_matrix04/)() const | Returns a value in 0-th row and 4-th column. |
| [get_Matrix10](./get_matrix10/)() const | Returns a value in 1-st row and 0-th column. |
| [get_Matrix11](./get_matrix11/)() const | Returns a value in 1-st row and 1-st column. |
| [get_Matrix12](./get_matrix12/)() const | Returns a value in 1-st row and 2-nd column. |
| [get_Matrix13](./get_matrix13/)() const | Returns a value in 1-st row and 3-rd column. |
| [get_Matrix14](./get_matrix14/)() const | Returns a value in 1-st row and 4-th column. |
| [get_Matrix20](./get_matrix20/)() const | Returns a value in 2-nd row and 0-th column. |
| [get_Matrix21](./get_matrix21/)() const | Returns a value in 2-nd row and 1-st column. |
| [get_Matrix22](./get_matrix22/)() const | Returns a value in 2-nd row and 2-nd column. |
| [get_Matrix23](./get_matrix23/)() const | Returns a value in 2-nd row and 3-rd column. |
| [get_Matrix24](./get_matrix24/)() const | Returns a value in 2-nd row and 4-th column. |
| [get_Matrix30](./get_matrix30/)() const | Returns a value in 3-rd row and 0-th column. |
| [get_Matrix31](./get_matrix31/)() const | Returns a value in 3-rd row and 1-st column. |
| [get_Matrix32](./get_matrix32/)() const | Returns a value in 3-rd row and 2-nd column. |
| [get_Matrix33](./get_matrix33/)() const | Returns a value in 3-rd row and 3-rd column. |
| [get_Matrix34](./get_matrix34/)() const | Returns a value in 3-rd row and 4-th column. |
| [get_Matrix40](./get_matrix40/)() const | Returns a value in 4-th row and 0-th column. |
| [get_Matrix41](./get_matrix41/)() const | Returns a value in 4-th row and 1-st column. |
| [get_Matrix42](./get_matrix42/)() const | Returns a value in 4-th row and 2-nd column. |
| [get_Matrix43](./get_matrix43/)() const | Returns a value in 4-th row and 3-rd column. |
| [get_Matrix44](./get_matrix44/)() const | Returns a value in 4-th row and 4-th column. |
| [idx_get](./idx_get/)(int, int) | Returns a value at the specified row and column. |
| [idx_set](./idx_set/)(int, int, float) | Sets the specifie value at the specified location in the matrix. |
| [set_Matrix00](./set_matrix00/)(float) | Sets a value in the 0-th row and 0-th column. |
| [set_Matrix01](./set_matrix01/)(float) | Sets a value in the 0-th row and 1-st column. |
| [set_Matrix02](./set_matrix02/)(float) | Sets a value in the 0-th row and 2-nd column. |
| [set_Matrix03](./set_matrix03/)(float) | Sets a value in the 0-th row and 3-rd column. |
| [set_Matrix04](./set_matrix04/)(float) | Sets a value in the 0-th row and 4-th column. |
| [set_Matrix10](./set_matrix10/)(float) | Sets a value in the 1-st row and 0-th column. |
| [set_Matrix11](./set_matrix11/)(float) | Sets a value in the 1-st row and 1-st column. |
| [set_Matrix12](./set_matrix12/)(float) | Sets a value in the 1-st row and 2-nd column. |
| [set_Matrix13](./set_matrix13/)(float) | Sets a value in the 1-st row and 3-rd column. |
| [set_Matrix14](./set_matrix14/)(float) | Sets a value in the 1-st row and 4-th column. |
| [set_Matrix20](./set_matrix20/)(float) | Sets a value in the 2-nd row and 0-th column. |
| [set_Matrix21](./set_matrix21/)(float) | Sets a value in the 2-nd row and 1-st column. |
| [set_Matrix22](./set_matrix22/)(float) | Sets a value in the 2-nd row and 2-nd column. |
| [set_Matrix23](./set_matrix23/)(float) | Sets a value in the 2-nd row and 3-rd column. |
| [set_Matrix24](./set_matrix24/)(float) | Sets a value in the 2-nd row and 4-th column. |
| [set_Matrix30](./set_matrix30/)(float) | Sets a value in the 3-rd row and 0-th column. |
| [set_Matrix31](./set_matrix31/)(float) | Sets a value in the 3-rd row and 1-st column. |
| [set_Matrix32](./set_matrix32/)(float) | Sets a value in the 3-rd row and 2-nd column. |
| [set_Matrix33](./set_matrix33/)(float) | Sets a value in the 3-rd row and 3-rd column. |
| [set_Matrix34](./set_matrix34/)(float) | Sets a value in the 3-rd row and 4-th column. |
| [set_Matrix40](./set_matrix40/)(float) | Sets a value in the 4-th row and 0-th column. |
| [set_Matrix41](./set_matrix41/)(float) | Sets a value in the 4-th row and 1-st column. |
| [set_Matrix42](./set_matrix42/)(float) | Sets a value in the 4-th row and 2-nd column. |
| [set_Matrix43](./set_matrix43/)(float) | Sets a value in the 4-th row and 3-rd column. |
| [set_Matrix44](./set_matrix44/)(float) | Sets a value in the 4-th row and 4-th column. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
