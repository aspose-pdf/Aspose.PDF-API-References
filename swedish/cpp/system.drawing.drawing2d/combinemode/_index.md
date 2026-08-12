---
title: "System::Drawing::Drawing2D::CombineMode enum"
linktitle: "CombineMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::CombineMode enum. Anger hur klippningsregioner kombineras i C++."
type: docs
weight: 1400
url: /sv/cpp/system.drawing.drawing2d/combinemode/
---
## CombineMode enum


Anger hur beskärningsregioner kombineras.

```cpp
enum class CombineMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ersätt | 0 | En klippningsregion ersätts av en annan. |
| Intersect | 1 | De två klippningsregionerna kombineras genom att ta deras skärningspunkt. |
| Union | 2 | De två beskärningsregionerna kombineras genom att ta unionen av båda. |
| Xor | 3 | De två beskärningsregionerna kombineras genom att endast ta området som omsluts av den ena eller den andra regionen, men inte båda. |
| Exkludera | 4 | Två beskärningsregioner kombineras genom att ta området av den första regionen som inte skär den andra. |
| Komplement | 5 | Två beskärningsregioner kombineras genom att ta området av den andra regionen som inte skär den första. |

## Se även

* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
