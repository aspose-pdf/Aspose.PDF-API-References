---
title: "System::Drawing::Drawing2D::CustomLineCap::CustomLineCap konstruktör"
linktitle: "CustomLineCap"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::CustomLineCap::CustomLineCap konstruktör. Skapar en ny instans av CustomLineCap-klassen som representerar en användardefinierad linjekåp med de angivna egenskaperna i C++."
type: docs
weight: 100
url: /sv/cpp/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap constructor


Skapar en ny instans av [CustomLineCap](../)-klassen som representerar en användardefinierad linjekåp med de angivna egenskaperna.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillPath | const SharedPtr\<GraphicsPath\>\& | Anger en fyllning för den anpassade kåpen |
| strokePath | const SharedPtr\<GraphicsPath\>\& | Anger en kontur för den anpassade kåpen |
| baseCap | LineCap | Den baslinjekap som den anpassade kappen skapas från |
| baseInset | float | Anger avståndet mellan linjen och kappen |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../graphicspath/)
* Enum [LineCap](../../linecap/)
* Class [CustomLineCap](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.PDF for C++](../../../)
