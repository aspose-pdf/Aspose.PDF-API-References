---
title: "Aspose::Pdf::Facades::PdfFileEditor::Insert метод"
linktitle: "Вставить"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::Insert метод. Вставляет страницы из другого файла во входной Pdf файл в C++."
type: docs
weight: 3200
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/insert/
---
## PdfFileEditor::Insert(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Вставляет страницы из другого файла во входной [Pdf](../../../aspose.pdf/) файл.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t insertLocation, const System::SharedPtr<System::IO::Stream> &portStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток [Pdf](../../../aspose.pdf/) файла. |
| insertLocation | int32_t | Позиция вставки во входном файле. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток [Pdf](../../../aspose.pdf/) файла для страниц. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Номер страницы, импортированной в portFile. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной поток. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Вставляет документ в другой документ и сохраняет результат в объект ответа.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t insertLocation, const System::SharedPtr<System::IO::Stream> &portStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток с исходным документом |
| insertLocation | int32_t | Место, куда будет вставлен другой документ. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | [Document](../../../aspose.pdf/document/) для вставки. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Массив номеров страниц во втором документе, которые будут вставлены. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект ответа, где будет сохранён результат. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Вставляет страницы из другого файла во входной [Pdf](../../../aspose.pdf/) файл.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t insertLocation, const System::SharedPtr<System::IO::Stream> &portStream, int32_t startPage, int32_t endPage, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток [Pdf](../../../aspose.pdf/) файла. |
| insertLocation | int32_t | Позиция вставки во входном файле. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток [Pdf](../../../aspose.pdf/) файла для страниц. |
| startPage | int32_t | С какой страницы начинать. |
| endPage | int32_t | На какой странице завершить. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной поток. |

### ReturnValue

True при успехе, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(const System::String\&, int32_t, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Вставляет содержимое файла в исходный файл и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::String &inputFile, int32_t insertLocation, const System::String &portFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Имя исходного файла. |
| insertLocation | int32_t | Номер [Page](../../../aspose.pdf/page/) где будет вставлен второй файл. |
| portFile | const System::String\& | Путь к файлу, который будет вставлен. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Массив номеров страниц в исходном файле, которые будут вставлены. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект ответа, где будет сохранён результат. |

### ReturnValue

true, если вставка была успешной.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(const System::String\&, int32_t, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Вставляет страницы из другого файла во входной [Pdf](../../../aspose.pdf/) файл.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::String &inputFile, int32_t insertLocation, const System::String &portFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Входной файл [Pdf](../../../aspose.pdf/). |
| insertLocation | int32_t | Позиция вставки во входном файле. |
| portFile | const System::String\& | Страницы из файла [Pdf](../../../aspose.pdf/). |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Номер страницы, импортированной в portFile. |
| outputFile | const System::String\& | Выводит файл [Pdf](../../../aspose.pdf/). |

### ReturnValue

True при успехе, иначе false.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(const System::String\&, int32_t, const System::String\&, int32_t, int32_t, const System::String\&) method


Вставляет страницы из другого файла в файл [Pdf](../../../aspose.pdf/) в указанной позиции.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::String &inputFile, int32_t insertLocation, const System::String &portFile, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Входной файл [Pdf](../../../aspose.pdf/). |
| insertLocation | int32_t | Позиция во входном файле. |
| portFile | const System::String\& | Файл портирования [Pdf](../../../aspose.pdf/). |
| startPage | int32_t | Начальная позиция в portFile. |
| endPage | int32_t | Конечная позиция в portFile. |
| outputFile | const System::String\& | Выводит файл [Pdf](../../../aspose.pdf/). |

### ReturnValue

True при успехе, иначе false.

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
