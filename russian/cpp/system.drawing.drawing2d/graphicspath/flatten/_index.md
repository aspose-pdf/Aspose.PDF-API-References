---
title: "System::Drawing::Drawing2D::GraphicsPath::Flatten метод"
linktitle: "Flatten"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Drawing2D::GraphicsPath::Flatten метод. Выравнивает каждую кривую в пути, преобразуя её в серию соединённых линий. Значение flatness 0.25 используется в C++."
type: docs
weight: 2100
url: /ru/cpp/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() method


Выравнивает каждую кривую в пути, преобразуя её в серию соединённых линий. Используется значение плоскостности 0.25.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## См. также

* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
## GraphicsPath::Flatten(const MatrixPtr\&) method


Выравнивает каждую кривую в пути, преобразуя её в серию соединённых линий. Используется значение плоскостности 0.25.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | const MatrixPtr\& | Матрица преобразования, применяемая к пути перед выравниванием |

## См. также

* Typedef [MatrixPtr](../../matrixptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
## GraphicsPath::Flatten(const MatrixPtr\&, float) method


Разглаживает каждую кривую в пути, преобразуя её в последовательность соединённых линий.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | const MatrixPtr\& | Матрица преобразования, применяемая к пути перед выравниванием |
| flatness | float | Указывает максимальную допустимую ошибку между кривой и её выровненной аппроксимацией |

## См. также

* Typedef [MatrixPtr](../../matrixptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
