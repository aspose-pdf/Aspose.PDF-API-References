---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryAppend метод"
linktitle: "TryAppend"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryAppend method. Добавляет страницы, выбранные из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов из portStreams в диапазоне от startPage до endPage в C++."
type: docs
weight: 6200
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/tryappend/
---
## PdfFileEditor::TryAppend(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Добавляет страницы, выбранные из массива документов в portStreams. Итоговый документ включает firstInputFile и все страницы документов из portStreams в диапазоне от startPage до endPage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryAppend(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &portStreams, int32_t startPage, int32_t endPage, const System::SharedPtr<System::IO::Stream> &outputStream)
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
## Примечания



Метод TryAppend похож на метод Append, за исключением того, что метод TryAppend не генерирует исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryAppend(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Добавляет документы к исходному документу и сохраняет результат в объект response.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryAppend(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &portStreams, int32_t startPage, int32_t endPage, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий исходный документ. |
| portStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Массив потоков с документами для добавления. |
| startPage | int32_t | Начальная страница добавляемой страницы. |
| endPage | int32_t | Конечная страница добавляемых страниц. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект ответа, где будет сохранён документ. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryAppend похож на метод Append, за исключением того, что метод TryAppend не генерирует исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryAppend(const System::String\&, const System::ArrayPtr\<System::String\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Добавляет документы к исходному документу и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryAppend(const System::String &inputFile, const System::ArrayPtr<System::String> &portFiles, int32_t startPage, int32_t endPage, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Имя файла, содержащего исходный документ. |
| portFiles | const System::ArrayPtr\<System::String\>\& | Массив имён файлов, содержащих присоединённые документы. |
| startPage | int32_t | Начальная страница присоединённых страниц. |
| endPage | int32_t | Конечная страница добавляемых страниц. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект ответа, где будет сохранён документ. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryAppend похож на метод Append, за исключением того, что метод TryAppend не генерирует исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryAppend(const System::String\&, const System::ArrayPtr\<System::String\>\&, int32_t, int32_t, const System::String\&) method


Добавляет страницы, выбранные из документов portFiles. Итоговый документ включает firstInputFile и все страницы документов из portFiles в диапазоне от startPage до endPage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryAppend(const System::String &inputFile, const System::ArrayPtr<System::String> &portFiles, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Входной файл [Pdf](../../../aspose.pdf/). |
| portFiles | const System::ArrayPtr\<System::String\>\& | Документы, из которых копировать страницы. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) начинается в документах portFiles. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) заканчивается в документах portFiles. |
| outputFile | const System::String\& | Выходной документ [Pdf](../../../aspose.pdf/). |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryAppend похож на метод Append, за исключением того, что метод TryAppend не генерирует исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
