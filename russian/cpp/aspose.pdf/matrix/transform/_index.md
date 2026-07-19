---
title: "Метод Aspose::Pdf::Matrix::Transform"
linktitle: "Transform"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Matrix::Transform. Преобразует прямоугольник. Если угол не равен 90 * N градусов, то возвращается ограничивающий прямоугольник в C++."
type: docs
weight: 2400
url: /ru/cpp/aspose.pdf/matrix/transform/
---
## Matrix::Transform(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Преобразует прямоугольник. Если угол не равен 90·N градусов, возвращается ограничивающий прямоугольник.

```cpp
System::SharedPtr<Aspose::Pdf::Rectangle> Aspose::Pdf::Matrix::Transform(const System::SharedPtr<Aspose::Pdf::Rectangle> &rect)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | [Rectangle](../../rectangle/) для преобразования. |

### ReturnValue

Преобразованный прямоугольник.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Rectangle](../../rectangle/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Transform(const System::SharedPtr\<Point\>\&) method


Преобразует точку, используя эту матрицу.

```cpp
System::SharedPtr<Point> Aspose::Pdf::Matrix::Transform(const System::SharedPtr<Point> &p)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| p | const System::SharedPtr\<Point\>\& | [Point](../../point/) который будет преобразован. |

### ReturnValue

Результат преобразования.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Point](../../point/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Transform(double, double, double\&, double\&) method


Преобразует координаты, используя эту матрицу.

```cpp
void Aspose::Pdf::Matrix::Transform(double x, double y, double &x1, double &y1)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Координата X. |
| y | double | Координата Y. |
| x1 | double\& | Преобразованная координата X. |
| y1 | double\& | Преобразованная координата Y. |

## См. также

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
