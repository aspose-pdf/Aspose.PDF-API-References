---
title: "Aspose::Pdf::Matrix::UnTransform metod"
linktitle: "UnTransform"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Matrix::UnTransform metod. Transformerar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med hjälp av följande formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B) i C++."
type: docs
weight: 2600
url: /sv/cpp/aspose.pdf/matrix/untransform/
---
## Matrix::UnTransform method


Omvandlar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med följande formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```cpp
void Aspose::Pdf::Matrix::UnTransform(double x1, double y1, double &x, double &y)
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
