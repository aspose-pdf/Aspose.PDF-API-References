---
title: "Aspose::Pdf::Document::Validate metod"
linktitle: "Validera"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document::Validate metod. Validera dokumentet till den angivna filen i C++."
type: docs
weight: 11600
url: /sv/cpp/aspose.pdf/document/validate/
---
## Document::Validate(const System::SharedPtr\<PdfFormatConversionOptions\>\&) method


Validera dokumentet till den angivna filen.

```cpp
bool Aspose::Pdf::Document::Validate(const System::SharedPtr<PdfFormatConversionOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | const System::SharedPtr\<PdfFormatConversionOptions\>\& | uppsättning alternativ för att konvertera PDF-dokument |

### ReturnValue

Resultatet av operationen

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Validate(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat) method


Validera dokumentet till den angivna filen.

```cpp
bool Aspose::Pdf::Document::Validate(const System::SharedPtr<System::IO::Stream> &outputLogStream, Aspose::Pdf::PdfFormat format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström där kommentarerna kommer att lagras. |
| format | Aspose::Pdf::PdfFormat | PDF-formatet. |

### ReturnValue

Resultatet av operationen

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [PdfFormat](../../pdfformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Validate(const System::String\&, Aspose::Pdf::PdfFormat) method


Validera dokumentet till den angivna filen.

```cpp
bool Aspose::Pdf::Document::Validate(const System::String &outputLogFileName, Aspose::Pdf::PdfFormat format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogFileName | const System::String\& | Sökväg till filen där kommentarerna kommer att lagras. |
| format | Aspose::Pdf::PdfFormat | PDF-formatet. |

### ReturnValue

Resultatet av operationen

## Se även

* Class [String](../../../system/string/)
* Enum [PdfFormat](../../pdfformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
