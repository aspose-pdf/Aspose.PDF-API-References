---
title: "Метод Aspose::Pdf::Facades::PdfFileEditor::Delete"
linktitle: "Удалить"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfFileEditor::Delete. Удаляет страницы, указанные массивом номеров, из входного файла, сохраняет как новый файл Pdf в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/delete/
---
## PdfFileEditor::Delete(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Удаляет страницы, указанные массивом номеров, из входного файла, сохраняет как новый файл [Pdf](../../../aspose.pdf/).

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной файловый поток. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Индекс страницы выходит за пределы входного файла. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток выходного файла. |

### ReturnValue

True при успехе, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Удаляет указанные страницы из документа и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток исходного документа. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Массив номеров страниц, которые будут удалены. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse |

### ReturnValue

True, если операция выполнена успешно.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Удаляет указанные страницы из документа и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь к исходному файлу. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Массив номеров страниц, которые необходимо удалить. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект Response, в котором будет храниться результирующий документ. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Удаляет страницы, указанные массивом номеров, из входного файла, сохраняет как новый файл [Pdf](../../../aspose.pdf/).

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь к входному файлу. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Индекс страницы выходит за пределы входного файла. |
| outputFile | const System::String\& | Путь к выходному файлу. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
