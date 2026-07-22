---
title: "Aspose::Pdf::Matrix::Transform metod"
linktitle: "Transform"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Matrix::Transform metod. Transformerar rektangel. Om vinkeln inte är 90 * N grader returneras omgivande rektangel i C++."
type: docs
weight: 2400
url: /sv/cpp/aspose.pdf/matrix/transform/
---
## Matrix::Transform(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Transformerar rektangel. Om vinkeln inte är 90 * N grader returneras omgivande rektangel.

```cpp
System::SharedPtr<Aspose::Pdf::Rectangle> Aspose::Pdf::Matrix::Transform(const System::SharedPtr<Aspose::Pdf::Rectangle> &rect)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | [Rectangle](../../rectangle/) att transformeras. |

### ReturnValue

Transformerad rektangel.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Rectangle](../../rectangle/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Transform(const System::SharedPtr\<Point\>\&) method


Transformerar punkt med denna matris.

```cpp
System::SharedPtr<Point> Aspose::Pdf::Matrix::Transform(const System::SharedPtr<Point> &p)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | const System::SharedPtr\<Point\>\& | [Point](../../point/) som kommer att transformeras. |

### ReturnValue

Transformationsresultat.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Point](../../point/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Transform(double, double, double\&, double\&) method


Transformerar koordinater med denna matris.

```cpp
void Aspose::Pdf::Matrix::Transform(double x, double y, double &x1, double &y1)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | double | X-koordinat. |
| y | double | Y-koordinat. |
| x1 | double\& | Transformerad X-koordinat. |
| y1 | double\& | Transformerad Y-koordinat. |

## Se även

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
