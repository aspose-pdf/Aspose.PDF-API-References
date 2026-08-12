---
title: "Aspose::Pdf::Matrix::Scale method"
linktitle: "Масштаб"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Matrix::Scale method. Масштабирует x и y с помощью матрицы, используя следующую формулу: x1 = A*x + C*y; y1 = B*x + D*y; в C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.pdf/matrix/scale/
---
## Matrix::Scale(double, double, double\&, double\&) method


Масштабирует x и y с помощью матрицы, используя следующую формулу: x1 = A*x + C*y; y1 = B*x + D*y;.

```cpp
void Aspose::Pdf::Matrix::Scale(double x, double y, double &x1, double &y1)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Входная координата X |
| y | double | Входная координата Y |
| x1 | double\& | Выходная координата X |
| y1 | double\& | Вывод координаты Y |

## См. также

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Scale(double, double, const System::SharedPtr\<Matrix\>\&) method


Применяет масштабирование к заданной матрице.

```cpp
static System::SharedPtr<Matrix> Aspose::Pdf::Matrix::Scale(double sx, double sy, const System::SharedPtr<Matrix> &source)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | double | Коэффициент масштабирования по оси X. |
| sy | double | Коэффициент масштабирования по оси Y. |
| источник | const System::SharedPtr\<Matrix\>\& | Матрица для масштабирования. |

### ReturnValue

Новая матрица, являющаяся результатом масштабирования исходной матрицы.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix](../)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
