---
title: "Aspose::Pdf::Matrix class"
linktitle: "Matrix"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Matrix class. Класс представляет преобразовательную матрицу в C++."
type: docs
weight: 10900
url: /ru/cpp/aspose.pdf/matrix/
---
## Matrix class


Класс представляет матрицу преобразования.

```cpp
class Matrix : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Matrix\>\&) | Добавляет матрицу к другой матрице. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Сравнивает матрицу с другим объектом. |
| [get_A](./get_a/)() | Элемент A преобразовательной матрицы. |
| [get_B](./get_b/)() | Элемент B преобразовательной матрицы. |
| [get_C](./get_c/)() | Элемент C преобразовательной матрицы. |
| [get_D](./get_d/)() | Элемент D преобразовательной матрицы. |
| [get_Data](./get_data/)() const | Получает данные [Matrix](./) в виде массива. |
| [get_E](./get_e/)() | Элемент E преобразовательной матрицы. |
| [get_Elements](./get_elements/)() | Элементы матрицы. |
| [get_F](./get_f/)() | Элемент F преобразовательной матрицы. |
| static [GetAngle](./getangle/)(Aspose::Pdf::Rotation) | Преобразует вращение в угол (градусы) |
| [GetFlipMatrix](./getflipmatrix/)() | Получает матрицу отражения. |
| [GetHashCode](./gethashcode/)() const override | Хеш-код объекта. |
| [Matrix](./matrix/)() | Конструктор создаёт стандартную матрицу 1 к 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]. |
| [Matrix](./matrix/)(const System::ArrayPtr\<double\>\&) | Конструктор принимает матрицу со следующим представлением массива: [ A B C D E F ]. |
| [Matrix](./matrix/)(const System::Details::ArrayView\<float\>\&) | Конструктор принимает матрицу со следующим представлением массива: [ A B C D E F ]. |
| [Matrix](./matrix/)(const System::SharedPtr\<Matrix\>\&) | Конструктор принимает матрицу для создания копии. |
| [Matrix](./matrix/)(double, double, double, double, double, double) | Инициализирует преобразовательную матрицу с указанными коэффициентами. |
| [Multiply](./multiply/)(const System::SharedPtr\<Matrix\>\&) | Умножает матрицу на другую матрицу. |
| [Reverse](./reverse/)() | Вычисляет обратную матрицу. |
| static [Rotation](./rotation/)(double) | Создаёт матрицу для заданного угла вращения. |
| static [Rotation](./rotation/)(Aspose::Pdf::Rotation) | Создаёт матрицу для заданного вращения. |
| [Scale](./scale/)(double, double, double\&, double\&) | Масштабирует x и y с помощью матрицы, используя следующую формулу: x1 = A*x + C*y; y1 = B*x + D*y;. |
| static [Scale](./scale/)(double, double, const System::SharedPtr\<Matrix\>\&) | Применяет масштабирование к заданной матрице. |
| [set_A](./set_a/)(double) | Элемент A преобразовательной матрицы. |
| [set_B](./set_b/)(double) | Элемент B преобразовательной матрицы. |
| [set_C](./set_c/)(double) | Элемент C преобразовательной матрицы. |
| [set_D](./set_d/)(double) | Элемент D преобразовательной матрицы. |
| [set_E](./set_e/)(double) | Элемент E преобразовательной матрицы. |
| [set_F](./set_f/)(double) | Элемент F преобразовательной матрицы. |
| static [Skew](./skew/)(double, double) | Создаёт матрицу для заданного угла вращения. |
| [ToString](./tostring/)() const override | Возвращает текстовое представление матрицы. |
| [Transform](./transform/)(const System::SharedPtr\<Point\>\&) | Преобразует точку, используя эту матрицу. |
| [Transform](./transform/)(double, double, double\&, double\&) | Преобразует координаты, используя эту матрицу. |
| [Transform](./transform/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Преобразует прямоугольник. Если угол не равен 90·N градусов, возвращается ограничивающий прямоугольник. |
| static [Translate](./translate/)(double, double, const System::SharedPtr\<Matrix\>\&) | Смещает матрицу на указанное значение по направлениям x и y. |
| [UnScale](./unscale/)(double, double, double\&, double\&) | Обратно масштабирует x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B);. |
| [UnTransform](./untransform/)(double, double, double\&, double\&) | Обратно преобразует x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
