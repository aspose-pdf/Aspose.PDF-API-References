---
title: "Aspose::Pdf::PageCoordinateType enum"
linktitle: "PageCoordinateType"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::PageCoordinateType enum. Описывает тип координат страницы в C++."
type: docs
weight: 25300
url: /ru/cpp/aspose.pdf/pagecoordinatetype/
---
## PageCoordinateType enum


Описывает тип координат страницы.

```cpp
enum class PageCoordinateType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| MediaBox | 0 | MediaBox используется для указания ширины и высоты страницы. Для обычного пользователя это, вероятно, соответствует фактическому размеру страницы. MediaBox — самый большой коробочный элемент страницы в PDF. Другие коробки страницы могут быть равны размеру MediaBox, но не могут быть больше. |
| CropBox | 1 | CropBox определяет область, к которой будет обрезано содержимое страницы. Acrobat использует этот размер для отображения на экране и печати. |

## См. также

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
