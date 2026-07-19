---
title: "Метод Aspose::Pdf::Matrix::UnScale"
linktitle: "UnScale"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Matrix::UnScale. Обратно масштабирует x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B); в C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.pdf/matrix/unscale/
---
## Matrix::UnScale method


Обратно масштабирует x1 и y1 и возвращает x и y до преобразования матрицы, используя следующую формулу: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B);.

```cpp
void Aspose::Pdf::Matrix::UnScale(double x1, double y1, double &x, double &y)
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
