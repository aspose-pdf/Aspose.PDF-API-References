---
title: "Aspose::Pdf::Facades::PdfConverter::BindPdf method"
linktitle: "BindPdf"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfConverter::BindPdf method. Vincula un documento PDF a la instancia PdfConverter para su posterior procesamiento en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.facades/pdfconverter/bindpdf/
---
## PdfConverter::BindPdf(System::SharedPtr\<Aspose::Pdf::Document\>) method


Vincula un documento PDF a la instancia [PdfConverter](../) para su posterior procesamiento.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::SharedPtr<Aspose::Pdf::Document> srcDoc) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcDoc | System::SharedPtr\<Aspose::Pdf::Document\> | El objeto [Document](../../../aspose.pdf/document/) que representa el PDF de origen que se va a vincular. |
## Observaciones



Este método inicializa el [PdfConverter](../) con el documento PDF especificado. También procesa formularios XFA dinámicos dentro del documento, si están presentes.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::BindPdf(System::SharedPtr\<System::IO::Stream\>) method


Vincula un flujo [Pdf](../../../aspose.pdf/) para convertir.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::SharedPtr<System::IO::Stream> inputStream) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | El flujo pdf. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::BindPdf(System::String) method


Vincula un archivo [Pdf](../../../aspose.pdf/) para convertir.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::String inputFile) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | System::String | El archivo pdf. |

## Ver también

* Class [String](../../../system/string/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
