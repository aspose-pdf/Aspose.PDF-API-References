---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryExtract метод"
linktitle: "TryExtract"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryExtract метод. Извлекает страницы, указанные массивом номеров, сохраняет как новый файл Pdf в C++."
type: docs
weight: 6500
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/tryextract/
---
## PdfFileEditor::TryExtract(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Извлекает страницы, указанные массивом номеров, сохраняет их как новый файл [Pdf](../../../aspose.pdf/).

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной файловый поток. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Индекс страницы выходит за пределы входного файла. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток выходного файла. |

### ReturnValue

True при успехе, иначе false.
## Примечания



Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток исходного документа. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Массив номеров страниц, которые будут извлечены. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь к исходному файлу. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Массив номеров страниц, которые будут извлечены. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не бросает исключение, если операция завершается неудачей.
## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Извлекает страницы, указанные массивом номеров, сохраняет как новый файл PDF.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь к входному файлу. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Индекс страницы выходит за пределы входного файла. |
| outputFile | const System::String\& | Путь к выходному файлу. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не бросает исключение, если операция завершается неудачей.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(const System::String\&, int32_t, int32_t, const System::String\&) method


Извлекает страницы из входного файла, сохраняет как новый файл [Pdf](../../../aspose.pdf/).

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::String &inputFile, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь к входному файлу [Pdf](../../../aspose.pdf/). |
| startPage | int32_t | Номер начальной страницы. |
| endPage | int32_t | Номер конечной страницы. |
| outputFile | const System::String\& | Путь к выходному файлу [Pdf](../../../aspose.pdf/). |

### ReturnValue

True при успехе, иначе false.
## Примечания



Метод TryExtract похож на метод Extract, за исключением того, что метод TryExtract не бросает исключение, если операция завершается неудачей.
## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
