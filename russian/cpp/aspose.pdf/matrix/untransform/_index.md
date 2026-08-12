---
title: "Aspose::Pdf::Matrix::UnTransform method"
linktitle: "UnTransform"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Matrix::UnTransform method. Обратно преобразует x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B) в C++."
type: docs
weight: 2600
url: /ru/cpp/aspose.pdf/matrix/untransform/
---
## Matrix::UnTransform method


Обратно преобразует x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```cpp
void Aspose::Pdf::Matrix::UnTransform(double x1, double y1, double &x, double &y)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x1 | double | Входная координата X |
| y1 | double | Входная координата Y |
| x | double\& | Выходная координата X |
| y | double\& | Вывод координаты Y |

## См. также

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
