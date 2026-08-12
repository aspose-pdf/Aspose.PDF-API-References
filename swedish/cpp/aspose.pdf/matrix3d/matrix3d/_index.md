---
title: "Aspose::Pdf::Matrix3D::Matrix3D konstruktor"
linktitle: "Matrix3D"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Matrix3D::Matrix3D konstruktor. Konstruktorn skapar en standard 1-till-1-matris: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D::Matrix3D() constructor


Konstruktorn skapar en standard 1 till 1-matris: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0].

```cpp
Aspose::Pdf::Matrix3D::Matrix3D()
```

## Se även

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(const System::ArrayPtr\<double\>\&) constructor


Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F G H I Tx Ty Tz].

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(const System::ArrayPtr<double> &matrix3DArray)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix3DArray | const System::ArrayPtr\<double\>\& | [Matrix](../../matrix/) dataarray. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(const System::SharedPtr\<Matrix3D\>\&) constructor


Konstruktor accepterar en matris för att skapa en kopia.

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(const System::SharedPtr<Matrix3D> &matrix)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | const System::SharedPtr\<Matrix3D\>\& | [Matrix3D](../) objekt. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix3D](../)
* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) constructor


Initierar transformationsmatris med angivna koefficienter.

```cpp
Aspose::Pdf::Matrix3D::Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | double | Ett matrisvärde. |
| b | double | B‑matrisvärde. |
| c | double | C‑matrisvärde. |
| d | double | D‑matrisvärde. |
| e | double | E‑matrisvärde. |
| f | double | F‑matrisvärde. |
| g | double | G matrisvärde. |
| h | double | H matrisvärde. |
| i | double | I matrisvärde. |
| tx | double | TX matrisvärde. |
| ty | double | TY matrisvärde. |
| tz | double | TZ matrisvärde. |

## Se även

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
