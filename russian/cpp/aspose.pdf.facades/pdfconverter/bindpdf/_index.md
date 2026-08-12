---
title: "Aspose::Pdf::Facades::PdfConverter::BindPdf method"
linktitle: "BindPdf"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfConverter::BindPdf method. Привязывает PDF-документ к экземпляру PdfConverter для дальнейшей обработки в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.facades/pdfconverter/bindpdf/
---
## PdfConverter::BindPdf(System::SharedPtr\<Aspose::Pdf::Document\>) method


Привязывает PDF‑документ к экземпляру [PdfConverter](../) для дальнейшей обработки.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::SharedPtr<Aspose::Pdf::Document> srcDoc) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | System::SharedPtr\<Aspose::Pdf::Document\> | Объект [Document](../../../aspose.pdf/document/), представляющий исходный PDF, который будет привязан. |
## Примечания



Этот метод инициализирует [PdfConverter](../) указанным PDF‑документом. Он также обрабатывает динамические формы XFA в документе, если они присутствуют.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::BindPdf(System::SharedPtr\<System::IO::Stream\>) method


Привязывает поток [Pdf](../../../aspose.pdf/) для конвертации.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::SharedPtr<System::IO::Stream> inputStream) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Поток PDF. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::BindPdf(System::String) method


Привязывает файл [Pdf](../../../aspose.pdf/) для конвертации.

```cpp
void Aspose::Pdf::Facades::PdfConverter::BindPdf(System::String inputFile) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | System::String | Файл PDF. |

## См. также

* Class [String](../../../system/string/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
