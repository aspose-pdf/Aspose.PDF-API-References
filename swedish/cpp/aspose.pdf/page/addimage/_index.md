---
title: "Aspose::Pdf::Page::AddImage metod"
linktitle: "AddImage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Page::AddImage metod. Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln och sparar bildens proportion i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf/page/addimage/
---
## Page::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, bool) method


Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportion bevaras.

```cpp
void Aspose::Pdf::Page::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, const System::SharedPtr<Aspose::Pdf::Rectangle> &imageRect, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr, bool autoAdjustRectangle=true)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för bilden. |
| imageRect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Positionen för bilden. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Bbox för bilden. |
| autoAdjustRectangle | bool | Justera bilden i mitten av den angivna rektangeln. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<Aspose::Pdf::Rectangle\>, int32_t, int32_t, bool, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Lägger till en bild på sidan och placerar den beroende på bildens rektangelposition.

```cpp
void Aspose::Pdf::Page::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, System::SharedPtr<Aspose::Pdf::Rectangle> imageRect, int32_t imageWidth, int32_t imageHeight, bool saveImageProportions, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för bilden. |
| imageRect | System::SharedPtr\<Aspose::Pdf::Rectangle\> | Standardpositionen för bilden på sidan. |
| imageWidth | int32_t | Bredden på bilden. |
| imageHeight | int32_t | Höjden på bilden. |
| saveImageProportions | bool | Om flaggan är satt till true placeras bilden i rektangelns position; annars blir rektangelns storlek lika med bildens storlek. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Bbox för bilden. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportion bevaras.

```cpp
void Aspose::Pdf::Page::AddImage(const System::String &hocr, const System::SharedPtr<System::IO::Stream> &imageStream, const System::SharedPtr<Aspose::Pdf::Rectangle> &imageRect, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hocr | const System::String\& | Hocr för bilden. |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för bilden. |
| imageRect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Positionen för bilden. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Bbox för bilden. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportion bevaras.

```cpp
void Aspose::Pdf::Page::AddImage(const System::String &imagePath, const System::SharedPtr<Aspose::Pdf::Rectangle> &rectangle)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imagePath | const System::String\& | Sökvägen till bilden. |
| rectangle | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Positionen för bilden. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
