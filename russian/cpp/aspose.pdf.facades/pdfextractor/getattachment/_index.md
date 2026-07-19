---
title: "Метод Aspose::Pdf::Facades::PdfExtractor::GetAttachment"
linktitle: "GetAttachment"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfExtractor::GetAttachment. Сохраняет все файлы вложений в потоки в C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.pdf.facades/pdfextractor/getattachment/
---
## PdfExtractor::GetAttachment() method


Сохраняет все файлы вложений в потоки.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfExtractor::GetAttachment()
```


### ReturnValue

Массив потоков файла вложения в pdf документе.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetAttachment(const System::String\&) method


Сохраняет вложение в файл.

```cpp
void Aspose::Pdf::Facades::PdfExtractor::GetAttachment(const System::String &outputPath)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputPath | const System::String\& | Путь к каталогу, где будут храниться вложения. Null или пустая строка означают, что вложения будут размещены в каталоге приложения. |

## См. также

* Class [String](../../../system/string/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
