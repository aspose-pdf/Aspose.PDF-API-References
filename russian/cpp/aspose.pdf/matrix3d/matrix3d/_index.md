---
title: "Конструктор Aspose::Pdf::Matrix3D::Matrix3D"
linktitle: "Matrix3D"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор Aspose::Pdf::Matrix3D::Matrix3D. Конструктор создает стандартную единичную матрицу: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D::Matrix3D() constructor


Конструктор создает стандартную матрицу 1 к 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0].

```cpp
Aspose::Pdf::Matrix3D::Matrix3D()
```

## См. также

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(const System::ArrayPtr\<double\>\&) constructor


Конструктор принимает матрицу со следующим представлением массива: [ A B C D E F G H I Tx Ty Tz].

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(const System::ArrayPtr<double> &matrix3DArray)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix3DArray | const System::ArrayPtr\<double\>\& | [Matrix](../../matrix/) массив данных. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(const System::SharedPtr\<Matrix3D\>\&) constructor


Конструктор принимает матрицу для создания копии.

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(const System::SharedPtr<Matrix3D> &matrix)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | const System::SharedPtr\<Matrix3D\>\& | [Matrix3D](../) объект. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix3D](../)
* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) constructor


Инициализирует преобразовательную матрицу с указанными коэффициентами.

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| a | double | Значение матрицы. |
| b | double | Значение матрицы B. |
| c | double | Значение C матрицы. |
| d | double | Значение D матрицы. |
| e | double | Значение E матрицы. |
| f | double | Значение F матрицы. |
| g | double | Значение матрицы G. |
| h | double | Значение матрицы H. |
| i | double | Значение матрицы I. |
| tx | double | Значение матрицы TX. |
| ty | double | Значение матрицы TY. |
| tz | double | Значение матрицы TZ. |

## См. также

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
