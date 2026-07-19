---
title: "Aspose::Pdf::Color::FromRgb метод"
linktitle: "FromRgb"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Color::FromRgb метод. Возвращает корректный объект pdf Color из компонентов RGB в C++."
type: docs
weight: 1300
url: /ru/cpp/aspose.pdf/color/fromrgb/
---
## Color::FromRgb(double, double, double) method


Возвращает корректный объект pdf [Color](../) из компонентов RGB.

```cpp
static System::SharedPtr<Color> Aspose::Pdf::Color::FromRgb(double r, double g, double b)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| r | double | Красный компонент цвета (значение 0 - 1). |
| g | double | Зелёный компонент цвета (значение 0 - 1). |
| b | double | Синий компонент цвета (значение 0 - 1). |

### ReturnValue

[Color](../) object with each component value in [0..1] range.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Color](../)
* Class [Color](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Color::FromRgb(System::Drawing::Color) method


Возвращает корректный объект pdf [Color](../) из значения [System.Drawing.Color](../../../system.drawing/color/).

```cpp
static System::SharedPtr<Color> Aspose::Pdf::Color::FromRgb(System::Drawing::Color color)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| color | System::Drawing::Color | Значение [System.Drawing.Color](../../../system.drawing/color/). |

### ReturnValue

[Color](../) object with each component value in [0..1] range.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Color](../)
* Class [Color](../../../system.drawing/color/)
* Class [Color](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
