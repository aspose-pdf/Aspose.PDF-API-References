---
title: "Aspose::Pdf::Facades::PdfConverter::BindPdf metod"
linktitle: "BindPdf"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfConverter::BindPdf metod. Binder ett PDF-dokument till PdfConverter-instansen för vidare bearbetning i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.facades/pdfconverter/bindpdf/
---
## PdfConverter::BindPdf(System::SharedPtr\<Aspose::Pdf::Document\>) method


Binder ett PDF-dokument till [PdfConverter](../)-instansen för vidare bearbetning.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::SharedPtr<Aspose::Pdf::Document> srcDoc) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcDoc | System::SharedPtr\<Aspose::Pdf::Document\> | Objektet [Document](../../../aspose.pdf/document/) som representerar käll-PDF:en som ska bindas. |
## Anmärkningar



Denna metod initierar [PdfConverter](../) med det angivna PDF-dokumentet. Den bearbetar också dynamiska XFA-formulär i dokumentet, om de finns.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::BindPdf(System::SharedPtr\<System::IO::Stream\>) method


Binder en [Pdf](../../../aspose.pdf/)-ström för konvertering.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::SharedPtr<System::IO::Stream> inputStream) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | PDF-strömmen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::BindPdf(System::String) method


Binder en [Pdf](../../../aspose.pdf/)-fil för konvertering.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::String inputFile) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | System::String | PDF-filen. |

## Se även

* Class [String](../../../system/string/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
