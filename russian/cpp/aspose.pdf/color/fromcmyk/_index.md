---
title: "Aspose::Pdf::Color::FromCmyk метод"
linktitle: "FromCmyk"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Color::FromCmyk метод. Получает корректный pdf‑объект Color из компонентов CMYK в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.pdf/color/fromcmyk/
---
## Color::FromCmyk method


Получает корректный pdf [Color](../) объект из компонентов CMYK.

```cpp
static System::SharedPtr<Color> Aspose::Pdf::Color::FromCmyk(double c, double m, double y, double k)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| c | double | Компонент цвета Cyan (значение 0 - 1). |
| m | double | Компонент цвета Magenta (значение 0 - 1). |
| y | double | Компонент цвета Yellow (значение 0 - 1). |
| k | double | Компонент цвета Key (значение 0 - 1). |

### ReturnValue

[Color](../) object with each component value in [0..1] range.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Color](../)
* Class [Color](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
