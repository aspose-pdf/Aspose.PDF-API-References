---
title: "Aspose::Pdf::Color::FromRgb método"
linktitle: "FromRgb"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Color::FromRgb método. Obtiene un objeto Color PDF válido a partir de los componentes de color RGB en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.pdf/color/fromrgb/
---
## Color::FromRgb(double, double, double) method


Obtiene un objeto [Color](../) PDF válido a partir de los componentes de color RGB.

```cpp
static System::SharedPtr<Color> Aspose::Pdf::Color::FromRgb(double r, double g, double b)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r | double | El componente de color rojo (valor 0 - 1). |
| g | double | El componente de color verde (valor 0 - 1). |
| b | double | El componente de color azul (valor 0 - 1). |

### ReturnValue

[Color](../) object with each component value in [0..1] range.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Color](../)
* Class [Color](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Color::FromRgb(System::Drawing::Color) method


Obtiene un objeto [Color](../) PDF válido a partir del valor [System.Drawing.Color](../../../system.drawing/color/).

```cpp
static System::SharedPtr<Color> Aspose::Pdf::Color::FromRgb(System::Drawing::Color color)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | System::Drawing::Color | Valor [System.Drawing.Color](../../../system.drawing/color/). |

### ReturnValue

[Color](../) object with each component value in [0..1] range.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Color](../)
* Class [Color](../../../system.drawing/color/)
* Class [Color](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
