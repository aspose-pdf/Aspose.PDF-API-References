---
title: "Aspose::Pdf::Facades::PdfExtractor::GetAttachment‑metod"
linktitle: "GetAttachment"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfExtractor::GetAttachment‑metod. Sparar alla bilagefiler till strömmar i C++."
type: docs
weight: 1400
url: /sv/cpp/aspose.pdf.facades/pdfextractor/getattachment/
---
## PdfExtractor::GetAttachment() method


Sparar alla bilagor till strömmar.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfExtractor::GetAttachment()
```


### ReturnValue

Strömarrayen för bilagefilen i pdf-dokumentet.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetAttachment(const System::String\&) method


Sparar bilagan i en fil.

```cpp
void Aspose::Pdf::Facades::PdfExtractor::GetAttachment(const System::String &outputPath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputPath | const System::String\& | Katalogsökväg där bilagor kommer att lagras. Null eller tom sträng betyder att bilagor placeras i applikationskatalogen. |

## Se även

* Class [String](../../../system/string/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
