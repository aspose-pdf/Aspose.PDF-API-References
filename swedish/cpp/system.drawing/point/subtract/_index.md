---
title: "System::Drawing::Point::Subtract metod"
linktitle: "Subtrahera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Point::Subtract metod. Subtraherar bredd‑ och höjdvärden för det angivna Size‑objektet från X‑ och Y‑koordinatvärdena för det angivna Point‑objektet på motsvarande sätt i C++."
type: docs
weight: 1800
url: /sv/cpp/system.drawing/point/subtract/
---
## Point::Subtract method


Subtraherar bredd‑ och höjdvärden för det angivna [Size](../../size/)‑objektet från X‑ och Y‑koordinatvärdena för det angivna [Point](../)‑objektet på motsvarande sätt.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| punkt | const Point\& | Punkten att förflytta |
| size | const Size\& | Det [Size](../../size/)‑objektet som specificerar värdena att subtrahera från koordinatavärdena för **point** |

### ReturnValue

Ett nytt [Point](../)‑objekt vars X‑koordinatvärde är lika med resultatet av subtraktionen av breddvärdet för **size** från X‑koordinatvärdet för **point**, och vars Y‑koordinatvärde är lika med resultatet av subtraktionen av höjdvärdet för **size** från Y‑koordinatvärdet för **point**.

## Se även

* Class [Point](../)
* Class [Size](../../size/)
* Class [Point](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
