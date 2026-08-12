---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet метод"
linktitle: "TryMakeBooklet"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet метод. Создаёт брошюру из PDF‑файла и сохраняет её в HttpResponse в C++."
type: docs
weight: 6700
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создаёт буклет из PDF‑файла и сохраняет его в HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток документа. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Желаемый размер страницы. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Массив номеров страниц, которые будут размещены слева. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Массив номеров страниц, которые будут размещены справа. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создает буклет из исходного файла и сохраняет результат в HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток документа. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Желаемый размер страницы в выходном файле. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект ответа, в котором будет сохранён результат. |

### ReturnValue

true, если буклет был успешно построен.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Создаёт буклет из InputStream в outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток pdf. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной поток pdf. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Создаёт пользовательский буклет из firstInputStream в outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной поток pdf. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Левые страницы. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Правые страницы. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) method


Создаёт буклет из входного потока и сохраняет результат в выходной поток.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток PDF. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной поток pdf. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы выходного pdf‑файла. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Создаёт буклет из firstInputStream в outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной поток pdf. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы выходного pdf‑файла. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Левые страницы. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Правые страницы. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создаёт буклет из исходного файла и сохраняет результат в объекты HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь к исходному файлу. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Желаемый размер страницы. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Массив номеров страниц, которые будут размещены слева. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Массив номеров страниц, которые будут размещены справа. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создаёт буклет из исходного файла и сохраняет результат в объекты HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь к исходному файлу. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Желаемый размер страницы в выходном файле. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

True, если операция завершилась успешно.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::String\&) method


Создаёт буклет из входного файла в выходной файл.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь и имя входного pdf‑файла. |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Создаёт пользовательский буклет из firstInputFile в outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Входной файл. |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Левые страницы буклета. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Правые страницы буклета. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::String\&, const System::SharedPtr\<PageSize\>\&) method


Создаёт буклет из inputFile в outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь и имя входного pdf‑файла. |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы выходного pdf‑файла. |

### ReturnValue

True, если операция завершилась успешно.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeBooklet(const System::String\&, const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Создаёт пользовательский буклет из firstInputFile в outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Входной файл. |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы выходного pdf‑файла. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Левые страницы. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Правые страницы. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeBooklet похож на метод MakeBooklet, за исключением того, что метод TryMakeBooklet не бросает исключение, если операция завершается неудачей.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
