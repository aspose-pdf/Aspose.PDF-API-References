---
title: "System::Drawing::Point::Add method"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Point::Add method. Lägger till bredd- och höjdvärdena för det angivna Size-objektet till X- och Y-koordinatvärdena för det angivna Point-objektet på motsvarande sätt i C++."
type: docs
weight: 1500
url: /sv/cpp/system.drawing/point/add/
---
## Point::Add method


Lägger till bredd- och höjdvärdena för det angivna [Size](../../size/) objektet till X- och Y-koordinatvärdena för det angivna [Point](../) objektet på motsvarande sätt.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| punkt | const Point\& | Punkten att förflytta |
| size | const Size\& | Det [Size](../../size/)‑objekt som specificerar värdena att lägga till koordinatvärdena för **point** |

### ReturnValue

Ett nytt [Point](../) objekt vars X-koordinatvärde är lika med summan av X-koordinatvärdet för **point** och breddvärdet för **size**, och Y-koordinatvärdet är lika med summan av Y-koordinatvärdet för **point** och höjdvärdet för **size**

## Se även

* Class [Point](../)
* Class [Size](../../size/)
* Class [Point](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
