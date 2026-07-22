---
title: "Aspose::Pdf::Facades::PdfFileMend::AddImage metod"
linktitle: "AddImage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileMend::AddImage metod. Lägger till en bild på de angivna sidorna i PDF‑dokumentet på angivna koordinater i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.facades/pdffilemend/addimage/
---
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) method


Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Indataström för bild. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Numren på de sidor som ska få bilden. |
| lowerLeftX | float | Den nedre vänstra x‑koordinaten för bildrektangeln. |
| lowerLeftY | float | Den nedre vänstra y‑koordinaten för bildrektangeln. |
| upperRightX | float | Den övre högra x‑koordinaten för bildrektangeln. |
| upperRightY | float | Den övre högra y‑koordinaten för bildrektangeln. |

### ReturnValue

True om lyckat, false annars.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Indataström för bild. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Numren på de sidor som ska få bilden. |
| lowerLeftX | float | Den nedre vänstra x‑koordinaten för bildrektangeln. |
| lowerLeftY | float | Den nedre vänstra y‑koordinaten för bildrektangeln. |
| upperRightX | float | Den övre högra x‑koordinaten för bildrektangeln. |
| upperRightY | float | Den övre högra y‑koordinaten för bildrektangeln. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Grafikens sammansättningsparametrar för bilderna. |

### ReturnValue

True om lyckat, false annars.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float) method


Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Indataström för bild. |
| pageNum | int32_t | Antalet sida som kommer att ta emot bilden. |
| lowerLeftX | float | Den nedre vänstra x‑koordinaten för bildrektangeln. |
| lowerLeftY | float | Den nedre vänstra y‑koordinaten för bildrektangeln. |
| upperRightX | float | Den övre högra x‑koordinaten för bildrektangeln. |
| upperRightY | float | Den övre högra y‑koordinaten för bildrektangeln. |

### ReturnValue

True om lyckat, false annars.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Indataström för bild. |
| pageNum | int32_t | Antalet sida som kommer att ta emot bilden. |
| lowerLeftX | float | Den nedre vänstra x‑koordinaten för bildrektangeln. |
| lowerLeftY | float | Den nedre vänstra y‑koordinaten för bildrektangeln. |
| upperRightX | float | Den övre högra x‑koordinaten för bildrektangeln. |
| upperRightY | float | Den övre högra y‑koordinaten för bildrektangeln. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Grafikens sammansättningsparametrar för bilden. |

### ReturnValue

True om lyckat, false annars.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) method


Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | const System::String\& | Sökvägen till inmatningsbildfilen. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Numren på de sidor som ska få bilden. |
| lowerLeftX | float | Den nedre vänstra x‑koordinaten för bildrektangeln. |
| lowerLeftY | float | Den nedre vänstra y‑koordinaten för bildrektangeln. |
| upperRightX | float | Den övre högra x‑koordinaten för bildrektangeln. |
| upperRightY | float | Den övre högra y‑koordinaten för bildrektangeln. |

### ReturnValue

True om lyckat, false annars.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | const System::String\& | Sökvägen till inmatningsbildfilen. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Numren på de sidor som ska få bilden. |
| lowerLeftX | float | Den nedre vänstra x‑koordinaten för bildrektangeln. |
| lowerLeftY | float | Den nedre vänstra y‑koordinaten för bildrektangeln. |
| upperRightX | float | Den övre högra x‑koordinaten för bildrektangeln. |
| upperRightY | float | Den övre högra y‑koordinaten för bildrektangeln. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Grafikens sammansättningsparametrar för bilderna. |

### ReturnValue

True om lyckat, false annars.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, int32_t, float, float, float, float) method


Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | const System::String\& | Sökvägen till inmatningsbildfilen. |
| pageNum | int32_t | Antalet sida som kommer att ta emot bilden. |
| lowerLeftX | float | Den nedre vänstra x‑koordinaten för bildrektangeln. |
| lowerLeftY | float | Den nedre vänstra y‑koordinaten för bildrektangeln. |
| upperRightX | float | Den övre högra x‑koordinaten för bildrektangeln. |
| upperRightY | float | Den övre högra y‑koordinaten för bildrektangeln. |

### ReturnValue

True om lyckat, false annars.

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageName | const System::String\& | Sökvägen till inmatningsbildfilen. |
| pageNum | int32_t | Antalet sida som kommer att ta emot bilden. |
| lowerLeftX | float | Den nedre vänstra x‑koordinaten för bildrektangeln. |
| lowerLeftY | float | Den nedre vänstra y‑koordinaten för bildrektangeln. |
| upperRightX | float | Den övre högra x‑koordinaten för bildrektangeln. |
| upperRightY | float | Den övre högra y‑koordinaten för bildrektangeln. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Grafikens sammansättningsparametrar för bilderna. |

### ReturnValue

True om lyckat, false annars.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
