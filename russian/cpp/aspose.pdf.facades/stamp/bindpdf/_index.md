---
title: "Метод Aspose::Pdf::Facades::Stamp::BindPdf"
linktitle: "BindPdf"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::Stamp::BindPdf. Устанавливает PDF‑файл и номер страницы, которые будут использоваться как штамп в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.facades/stamp/bindpdf/
---
## Stamp::BindPdf(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) method


Устанавливает PDF‑файл и номер страницы, которые будут использоваться в качестве штампа.

```cpp
void Aspose::Pdf::Facades::Stamp::BindPdf(const System::SharedPtr<System::IO::Stream> &pdfStream, int32_t pageNumber)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий PDF‑документ. |
| pageNumber | int32_t | Индекс [Page](../../../aspose.pdf/page/) документа, который будет использоваться как штамп. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Stamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Stamp::BindPdf(const System::String\&, int32_t) method


Устанавливает PDF‑файл и номер страницы, которые будут использоваться в качестве штампа.

```cpp
void Aspose::Pdf::Facades::Stamp::BindPdf(const System::String &pdfFile, int32_t pageNumber)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfFile | const System::String\& | Путь к PDF‑файлу. |
| pageNumber | int32_t | Номер страницы в PDF‑файле |

## См. также

* Class [String](../../../system/string/)
* Class [Stamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
