---
title: "Метод Aspose::Pdf::Document::Validate"
linktitle: "Валидация"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Document::Validate. Проверяет документ и сохраняет в указанный файл в C++."
type: docs
weight: 11600
url: /ru/cpp/aspose.pdf/document/validate/
---
## Document::Validate(const System::SharedPtr\<PdfFormatConversionOptions\>\&) method


Проверить документ в указанный файл.

```cpp
bool Aspose::Pdf::Document::Validate(const System::SharedPtr<PdfFormatConversionOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| опции | const System::SharedPtr\<PdfFormatConversionOptions\>\& | набор параметров для преобразования PDF‑документа |

### ReturnValue

Результат операции

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Validate(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat) method


Проверить документ в указанный файл.

```cpp
bool Aspose::Pdf::Document::Validate(const System::SharedPtr<System::IO::Stream> &outputLogStream, Aspose::Pdf::PdfFormat format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будут сохраняться комментарии. |
| формат | Aspose::Pdf::PdfFormat | PDF‑формат. |

### ReturnValue

Результат операции

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [PdfFormat](../../pdfformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Validate(const System::String\&, Aspose::Pdf::PdfFormat) method


Проверить документ в указанный файл.

```cpp
bool Aspose::Pdf::Document::Validate(const System::String &outputLogFileName, Aspose::Pdf::PdfFormat format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | const System::String\& | Путь к файлу, в котором будут сохраняться комментарии. |
| формат | Aspose::Pdf::PdfFormat | PDF‑формат. |

### ReturnValue

Результат операции

## См. также

* Class [String](../../../system/string/)
* Enum [PdfFormat](../../pdfformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
