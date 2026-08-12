---
title: "Aspose::Pdf::PdfPageStamp::PdfPageStamp конструктор"
linktitle: "PdfPageStamp"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::PdfPageStamp::PdfPageStamp конструктор. Конструктор PdfPageStamp в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf/pdfpagestamp/pdfpagestamp/
---
## PdfPageStamp::PdfPageStamp(const System::SharedPtr\<Page\>\&) constructor


Конструктор [PdfPageStamp](../).

```cpp
Aspose::Pdf::PdfPageStamp::PdfPageStamp(const System::SharedPtr<Page> &pdfPage)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfPage | const System::SharedPtr\<Page\>\& | [Page](../../page/) который используется для штамповки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PdfPageStamp](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfPageStamp::PdfPageStamp(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) constructor


Создаёт штамп страницы [Pdf](../../) из указанной страницы документа из потока.

```cpp
Aspose::Pdf::PdfPageStamp::PdfPageStamp(const System::SharedPtr<System::IO::Stream> &stream, int32_t pageIndex)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий PDF |
| pageIndex | int32_t | Индекс страницы. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfPageStamp](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfPageStamp::PdfPageStamp(const System::String\&, int32_t) constructor


Создаёт штамп страницы [Pdf](../../) из указанной страницы документа в указанном файле.

```cpp
Aspose::Pdf::PdfPageStamp::PdfPageStamp(const System::String &fileName, int32_t pageIndex)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | const System::String\& | Имя и страница PDF‑файла. |
| pageIndex | int32_t | Индекс страницы. |

## См. также

* Class [String](../../../system/string/)
* Class [PdfPageStamp](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
