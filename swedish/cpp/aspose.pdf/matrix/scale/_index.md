---
title: "Aspose::Pdf::Matrix::Scale metod"
linktitle: "Scale"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Matrix::Scale metod. Skalar x och y med matrisen med hjälp av följande formel: x1 = A*x + C*y; y1 = B*x + D*y; i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.pdf/matrix/scale/
---
## Matrix::Scale(double, double, double\&, double\&) method


Skalar x och y med matrisen med följande formel: x1 = A*x + C*y; y1 = B*x + D*y;.

```cpp
void Aspose::Pdf::Matrix::Scale(double x, double y, double &x1, double &y1)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | double | Indata X-koordinat |
| y | double | Indata Y-koordinat |
| x1 | double\& | Utdata X-koordinat |
| y1 | double\& | Utdata Y-koordinat |

## Se även

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Scale(double, double, const System::SharedPtr\<Matrix\>\&) method


Tillämpar skalning på den givna matrisen.

```cpp
static System::SharedPtr<Matrix> Aspose::Pdf::Matrix::Scale(double sx, double sy, const System::SharedPtr<Matrix> &source)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | double | Skalfaktorn för X‑axeln. |
| sy | double | Skalfaktorn för Y‑axeln. |
| source | const System::SharedPtr\<Matrix\>\& | Matrisen som ska skalas. |

### ReturnValue

En ny matris som är resultatet av att skala källmatrisen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix](../)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
