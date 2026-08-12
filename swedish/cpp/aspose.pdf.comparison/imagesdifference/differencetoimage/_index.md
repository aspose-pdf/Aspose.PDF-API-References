---
title: "Aspose::Pdf::Comparison::ImagesDifference::DifferenceToImage metod"
linktitle: "DifferenceToImage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::ImagesDifference::DifferenceToImage metod. Konverterar skillnadsarrayen till en bitmap-bild med de angivna färgerna i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.comparison/imagesdifference/differencetoimage/
---
## ImagesDifference::DifferenceToImage method


Konverterar skillnadsarrayen till en bitmap‑bild med de angivna färgerna.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Pdf::Comparison::ImagesDifference::DifferenceToImage(const System::SharedPtr<Color> &color, const System::SharedPtr<Color> &backgroundColor)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| färg | const System::SharedPtr\<Color\>\& | Färgen för icke‑nollskillnader. |
| backgroundColor | const System::SharedPtr\<Color\>\& | Bakgrundsfärgen för nollskillnader. |

### ReturnValue

En bitmap-bild som representerar skillnadsarrayen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [Color](../../../aspose.pdf/color/)
* Class [ImagesDifference](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
