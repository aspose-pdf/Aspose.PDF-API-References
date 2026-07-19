---
title: "Метод Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp"
linktitle: "TryMakeNUp"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp. Создаёт документ N‑Up из нескольких входных PDF‑потоков в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые являются комбинацией страниц во входных потоках с одинаковым номером страницы. Многостраничные элементы укладываются горизонтально, если isSidewise равно true, и вертикально, если isSidewise равно false в C++."
type: docs
weight: 6800
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## PdfFileEditor::TryMakeNUp(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::SharedPtr\<System::IO::Stream\>\&, bool) method


Создает N‑Up документ из нескольких входных PDF‑потоков в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые являются комбинацией страниц входных потоков с одинаковыми номерами. Эти несколько страниц размещаются горизонтально, если isSidewise равно true, и вертикально, если isSidewise равно false.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &inputStreams, const System::SharedPtr<System::IO::Stream> &outputStream, bool isSidewise)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Входные потоки [Pdf](../../../aspose.pdf/). |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной PDF‑поток. |
| isSidewise | bool | Способ укладки: true — горизонтально, false — вертикально. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::ArrayPtr\<System::String\>\&, const System::String\&, bool) method


Создает N‑Up документ из нескольких входных PDF‑файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией страниц входных файлов с одинаковыми номерами. Эти несколько страниц размещаются горизонтально, если isSidewise равно true, и вертикально, если isSidewise равно false.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::ArrayPtr<System::String> &inputFiles, const System::String &outputFile, bool isSidewise)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | const System::ArrayPtr\<System::String\>\& | Входные файлы [Pdf](../../../aspose.pdf/). |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |
| isSidewise | bool | Способ укладки: true — горизонтально, false — вертикально. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Создает N‑Up документ из двух входных PDF‑потоков в outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &firstInputStream, const System::SharedPtr<System::IO::Stream> &secondInputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | const System::SharedPtr\<System::IO::Stream\>\& | Первый входной поток. |
| secondInputStream | const System::SharedPtr\<System::IO::Stream\>\& | Второй входной поток. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной PDF‑поток. |

### ReturnValue

true, если операция завершилась успешно; иначе false
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t) method


Создает N‑Up документ из входного потока и сохраняет результат в выходной поток.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, int32_t x, int32_t y)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток pdf. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной PDF‑поток. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&) method


Создает N‑Up документ из первого входного потока в выходной поток.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток pdf. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной PDF‑поток. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы выходного pdf‑файла. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создает N‑up документ и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток исходного документа. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер [Page](../../../aspose.pdf/page/) в результирующем файле. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создает N‑up документ и сохраняет результат в HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t x, int32_t y, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток входного документа. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse, в котором будет сохранён результат. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, const System::String\&, const System::String\&) method


Создает N‑Up документ из двух входных PDF‑файлов в outputFile. Каждая страница outputFile будет содержать две страницы: одна из первого входного файла, другая — из второго входного файла. Эти две страницы размещаются горизонтально.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &firstInputFile, const System::String &secondInputFile, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | const System::String\& | Первый входной файл. |
| secondInputFile | const System::String\& | Второй входной файл. |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |

### ReturnValue

true, если операция завершилась успешно; иначе false
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, const System::String\&, int32_t, int32_t) method


Создает N‑Up документ из firstInputFile в outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, const System::String &outputFile, int32_t x, int32_t y)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь и имя входного pdf‑файла. |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, const System::String\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&) method


Создает N‑Up документ из входного файла в outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, const System::String &outputFile, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь и имя входного pdf‑файла. |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы выходного pdf‑файла. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создает N‑up документ и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь к исходному файлу. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер [Page](../../../aspose.pdf/page/) в результирующем файле. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создает N‑up документ и сохраняет результат в HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, int32_t x, int32_t y, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Имя исходного файла. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryMakeNUp похож на метод MakeNUp, за исключением того, что метод TryMakeNUp не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
