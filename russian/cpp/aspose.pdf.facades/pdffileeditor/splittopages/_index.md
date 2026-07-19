---
title: "Aspose::Pdf::Facades::PdfFileEditor::SplitToPages method"
linktitle: "SplitToPages"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::SplitToPages method. Делит Pdf файл на одностраничные документы в C++."
type: docs
weight: 6100
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/splittopages/
---
## PdfFileEditor::SplitToPages(const System::SharedPtr\<System::IO::Stream\>\&) method


Разделяет файл [Pdf](../../../aspose.pdf/) на одностраничные документы.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::SharedPtr<System::IO::Stream> &inputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной [Pdf](../../../aspose.pdf/) поток. |

### ReturnValue

Массив потоков памяти, содержащих страницы документа.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Разделите файл [Pdf](../../../aspose.pdf/) на одностраничные документы и сохраните его в указанный путь. Путь задаётся полем fileNameTemplate.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::SharedPtr<System::IO::Stream> &inputStream, const System::String &fileNameTemplate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток исходного документа. |
| fileNameTemplate | const System::String\& | Шаблон имени результирующего файла. Должен содержать NUM%, который заменяется номером страницы. Например, если указано c:/dir/pageNUM%.pdf, полученные файлы будут иметь следующие имена: c:/dir/page1.pdf, c:/dir/page2.pdf и т.д. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(const System::String\&) method


Разделяет PDF‑файл на одностраничные документы.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::String &inputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Имя входного PDF файла. |

### ReturnValue

Потоки вывода PDF, каждый поток содержит одностраничный PDF документ.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(const System::String\&, const System::String\&) method


Разделите файл [Pdf](../../../aspose.pdf/) на одностраничные документы и сохраните его в указанный путь. Путь задаётся полем fileNameTemplate.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::String &inputFile, const System::String &fileNameTemplate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Имя входного файла. |
| fileNameTemplate | const System::String\& | Шаблон имени результирующего файла. Должен содержать NUM%, который заменяется номером страницы. Например, если указано c:/dir/pageNUM%.pdf, полученные файлы будут иметь следующие имена: c:/dir/page1.pdf, c:/dir/page2.pdf и т.д. |

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
