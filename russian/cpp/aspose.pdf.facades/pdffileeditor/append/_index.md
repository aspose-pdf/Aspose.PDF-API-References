---
title: "Aspose::Pdf::Facades::PdfFileEditor::Append метод"
linktitle: "Добавить"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::Append метод. Добавляет страницы, выбранные из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов из portStreams в диапазоне от startPage до endPage в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/append/
---
## PdfFileEditor::Append(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Добавляет страницы, выбранные из массива документов в portStreams. Итоговый документ включает firstInputFile и все страницы документов из portStreams в диапазоне от startPage до endPage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &portStreams, int32_t startPage, int32_t endPage, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной [Pdf](../../../aspose.pdf/) поток. |
| portStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Документы, из которых копировать страницы. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) начинается в документах portStreams. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) заканчивается в документах portStreams. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной [Pdf](../../../aspose.pdf/) поток. |

### ReturnValue

True при успехе, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Добавляет документы к исходному документу и сохраняет результат в объект response.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &portStreams, int32_t startPage, int32_t endPage, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий исходный документ. |
| portStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Массив потоков с документами для добавления. |
| startPage | int32_t | Начальная страница добавляемой страницы. |
| endPage | int32_t | Конечная страница добавляемых страниц. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект ответа, где будет сохранён документ. |

### ReturnValue

true, если операция была успешной.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Добавляет страницы, выбранные из portStream в диапазоне от startPage до endPage, в portStream в конец firstInputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &portStream, int32_t startPage, int32_t endPage, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной файловый поток. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | Страницы из [Pdf](../../../aspose.pdf/) файлового потока. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) начинается в потоке portFile. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) заканчивается в потоке portFile. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной [Pdf](../../../aspose.pdf/) файловый поток. |

### ReturnValue

True при успехе, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::String\&, const System::ArrayPtr\<System::String\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Добавляет документы к исходному документу и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::String &inputFile, const System::ArrayPtr<System::String> &portFiles, int32_t startPage, int32_t endPage, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Имя файла, содержащего исходный документ. |
| portFiles | const System::ArrayPtr\<System::String\>\& | Массив имён файлов, содержащих присоединённые документы. |
| startPage | int32_t | Начальная страница присоединённых страниц. |
| endPage | int32_t | Конечная страница добавляемых страниц. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект ответа, где будет сохранён документ. |

### ReturnValue

true, если операция завершилась успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::String\&, const System::ArrayPtr\<System::String\>\&, int32_t, int32_t, const System::String\&) method


Добавляет страницы, выбранные из документов portFiles. Итоговый документ включает firstInputFile и все страницы документов из portFiles в диапазоне от startPage до endPage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::String &inputFile, const System::ArrayPtr<System::String> &portFiles, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Входной файл [Pdf](../../../aspose.pdf/). |
| portFiles | const System::ArrayPtr\<System::String\>\& | Документы, из которых копировать страницы. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) начинается в документах portFiles. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) заканчивается в документах portFiles. |
| outputFile | const System::String\& | Выходной документ [Pdf](../../../aspose.pdf/). |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::String\&, const System::String\&, int32_t, int32_t, const System::String\&) method


Добавляет страницы, выбранные из portFile в диапазоне от startPage до endPage, в portFile в конец firstInputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::String &inputFile, const System::String &portFile, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Входной файл [Pdf](../../../aspose.pdf/). |
| portFile | const System::String\& | Страницы из файла [Pdf](../../../aspose.pdf/). |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) начинается в portFile. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) заканчивается в portFile. |
| outputFile | const System::String\& | Выходной документ [Pdf](../../../aspose.pdf/). |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
