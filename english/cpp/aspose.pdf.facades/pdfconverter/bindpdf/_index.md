---
title: Aspose::Pdf::Facades::PdfConverter::BindPdf method
linktitle: BindPdf
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfConverter::BindPdf method. Binds a PDF document to the PdfConverter instance for further processing in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.facades/pdfconverter/bindpdf/
---
## PdfConverter::BindPdf(System::SharedPtr\<Aspose::Pdf::Document\>) method


Binds a PDF document to the [PdfConverter](../) instance for further processing.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::SharedPtr<Aspose::Pdf::Document> srcDoc) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | System::SharedPtr\<Aspose::Pdf::Document\> | The [Document](../../../aspose.pdf/document/) object representing the source PDF to be bound. |
## Remarks



This method initializes the [PdfConverter](../) with the specified PDF document. It also processes dynamic XFA forms within the document, if present. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::BindPdf(System::SharedPtr\<System::IO::Stream\>) method


Binds a [Pdf](../../../aspose.pdf/) Stream for convert.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::SharedPtr<System::IO::Stream> inputStream) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | The pdf Stream. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::BindPdf(System::String) method


Binds a [Pdf](../../../aspose.pdf/) file for converting.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::String inputFile) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | The pdf file. |

## See Also

* Class [String](../../../system/string/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
