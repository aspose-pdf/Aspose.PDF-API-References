---
title: "Aspose::Pdf::Matrix::UnScale metod"
linktitle: "UnScale"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Matrix::UnScale metod. Skalar tillbaka x1 och y1 och returnerar x och y före matristransformeringen med följande formel: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B); i C++."
type: docs
weight: 2500
url: /sv/cpp/aspose.pdf/matrix/unscale/
---
## Matrix::UnScale method


Skalar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med följande formel: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);.

```cpp
void Aspose::Pdf::Matrix::UnScale(double x1, double y1, double &x, double &y)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | double | Indata X-koordinat |
| y1 | double | Indata Y-koordinat |
| x | double\& | Utdata X-koordinat |
| y | double\& | Utdata Y-koordinat |

## Se även

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
