---
title: "Aspose::Pdf::Facades::PdfExtractor::GetNextImage metod"
linktitle: "GetNextImage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfExtractor::GetNextImage metod. Hämtar nästa bild från PDF-filen och lagrar den i en ström i C++."
type: docs
weight: 1700
url: /sv/cpp/aspose.pdf.facades/pdfextractor/getnextimage/
---
## PdfExtractor::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&) method


Hämtar nästa bild från PDF‑filen och sparar den i en ström.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström där bilddata kommer att sparas |

### ReturnValue

Sant om bilden har extraherats framgångsrikt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Hämtar nästa bild från PDF‑filen och sparar den i en ström med angivet bildformat.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström där bilddata kommer att sparas |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |

### ReturnValue

Sant om bilden har extraherats framgångsrikt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::String\&) method


Hämtar nästa bild från PDF-dokumentet. [Obs](../../../aspose.pdf/note/): ExtractImage måste anropas innan denna metod används.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Fil där bilden kommer att lagras |

### ReturnValue

Sant om bilden har extraherats framgångsrikt

## Se även

* Class [String](../../../system/string/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Hämtar nästa bild från PDF-dokumentet med angivet bildformat. [Obs](../../../aspose.pdf/note/): ExtractImage måste anropas innan denna metod används.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Fil där bilden kommer att lagras |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |

### ReturnValue

Sant om bilden har extraherats framgångsrikt

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
