---
title: "Класс Aspose::Pdf::Matrix3D"
linktitle: "Matrix3D"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Matrix3D. Класс представляет матрицу преобразования в C++."
type: docs
weight: 11000
url: /ru/cpp/aspose.pdf/matrix3d/
---
## Matrix3D class


Класс представляет матрицу преобразования.

```cpp
class Matrix3D : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Matrix3D\>\&) | Добавляет матрицу к другой матрице. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Сравнивает матрицу с другим объектом. |
| [get_A](./get_a/)() | Элемент A преобразовательной матрицы. |
| [get_B](./get_b/)() | Элемент B преобразовательной матрицы. |
| [get_C](./get_c/)() | Элемент C преобразовательной матрицы. |
| [get_D](./get_d/)() | Элемент D преобразовательной матрицы. |
| [get_E](./get_e/)() | Элемент E преобразовательной матрицы. |
| [get_F](./get_f/)() | Элемент F преобразовательной матрицы. |
| [get_G](./get_g/)() | Элемент G матрицы преобразования. |
| [get_H](./get_h/)() | Элемент H матрицы преобразования. |
| [get_I](./get_i/)() | Элемент I матрицы преобразования. |
| [get_Tx](./get_tx/)() | Элемент Tx матрицы преобразования. |
| [get_Ty](./get_ty/)() | Элемент Ty матрицы преобразования. |
| [get_Tz](./get_tz/)() | Элемент Tz матрицы преобразования. |
| static [GetAngle](./getangle/)(Rotation) | Преобразует вращение в угол (градусы) |
| [GetHashCode](./gethashcode/)() const override | Хеш-код объекта. |
| [Matrix3D](./matrix3d/)() | Конструктор создает стандартную матрицу 1 к 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]. |
| [Matrix3D](./matrix3d/)(const System::ArrayPtr\<double\>\&) | Конструктор принимает матрицу со следующим представлением массива: [ A B C D E F G H I Tx Ty Tz]. |
| [Matrix3D](./matrix3d/)(const System::SharedPtr\<Matrix3D\>\&) | Конструктор принимает матрицу для создания копии. |
| [Matrix3D](./matrix3d/)(double, double, double, double, double, double, double, double, double, double, double, double) | Инициализирует преобразовательную матрицу с указанными коэффициентами. |
| [set_A](./set_a/)(double) | Элемент A преобразовательной матрицы. |
| [set_B](./set_b/)(double) | Элемент B преобразовательной матрицы. |
| [set_C](./set_c/)(double) | Элемент C преобразовательной матрицы. |
| [set_D](./set_d/)(double) | Элемент D преобразовательной матрицы. |
| [set_E](./set_e/)(double) | Элемент E преобразовательной матрицы. |
| [set_F](./set_f/)(double) | Элемент F преобразовательной матрицы. |
| [set_G](./set_g/)(double) | Элемент G матрицы преобразования. |
| [set_H](./set_h/)(double) | Элемент H матрицы преобразования. |
| [set_I](./set_i/)(double) | Элемент I матрицы преобразования. |
| [set_Tx](./set_tx/)(double) | Элемент Tx матрицы преобразования. |
| [set_Ty](./set_ty/)(double) | Элемент Ty матрицы преобразования. |
| [set_Tz](./set_tz/)(double) | Элемент Tz матрицы преобразования. |
| [ToString](./tostring/)() const override | Возвращает текстовое представление матрицы. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
