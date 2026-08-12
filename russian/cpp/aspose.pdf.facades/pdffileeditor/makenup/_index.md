---
title: "Aspose::Pdf::Facades::PdfFileEditor::MakeNUp метод"
linktitle: "MakeNUp"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::MakeNUp method. Создает N-Up документ из нескольких входных PDF потоков в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые являются комбинацией страниц входных потоков с тем же номером. Многостраничные страницы укладываются горизонтально, если isSidewise равно true, и вертикально, если isSidewise равно false в C++."
type: docs
weight: 3400
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/makenup/
---
## PdfFileEditor::MakeNUp(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::SharedPtr\<System::IO::Stream\>\&, bool) method


Создает N‑Up документ из нескольких входных PDF‑потоков в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые являются комбинацией страниц входных потоков с одинаковыми номерами. Эти несколько страниц размещаются горизонтально, если isSidewise равно true, и вертикально, если isSidewise равно false.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &inputStreams, const System::SharedPtr<System::IO::Stream> &outputStream, bool isSidewise)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Входные потоки [Pdf](../../../aspose.pdf/). |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной PDF‑поток. |
| isSidewise | bool | Способ укладки: true — горизонтально, false — вертикально. |

### ReturnValue

boolean — True при успехе, иначе false.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::ArrayPtr\<System::String\>\&, const System::String\&, bool) method


Создает N‑Up документ из нескольких входных PDF‑файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией страниц входных файлов с одинаковыми номерами. Эти несколько страниц размещаются горизонтально, если isSidewise равно true, и вертикально, если isSidewise равно false.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::ArrayPtr<System::String> &inputFiles, const System::String &outputFile, bool isSidewise)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | const System::ArrayPtr\<System::String\>\& | Входные файлы [Pdf](../../../aspose.pdf/). |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |
| isSidewise | bool | Способ укладки: true — горизонтально, false — вертикально. |

### ReturnValue

boolean — True при успехе, иначе false.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Создает N‑Up документ из двух входных PDF‑потоков в outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::SharedPtr<System::IO::Stream> &firstInputStream, const System::SharedPtr<System::IO::Stream> &secondInputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | const System::SharedPtr\<System::IO::Stream\>\& | Первый входной поток. |
| secondInputStream | const System::SharedPtr\<System::IO::Stream\>\& | Второй входной поток. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной PDF‑поток. |

### ReturnValue

boolean — True при успехе, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t) method


Создает N‑Up документ из входного потока и сохраняет результат в выходной поток.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, int32_t x, int32_t y)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток pdf. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной PDF‑поток. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |

### ReturnValue

boolean — True при успехе, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&) method


Создает N‑Up документ из первого входного потока в выходной поток.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток pdf. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной PDF‑поток. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы выходного pdf‑файла. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создает N‑up документ и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток исходного документа. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер [Page](../../../aspose.pdf/page/) в результирующем файле. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создает N‑up документ и сохраняет результат в HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t x, int32_t y, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток входного документа. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse, в котором будет сохранён результат. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::String\&, const System::String\&, const System::String\&) method


Создает N‑Up документ из двух входных PDF‑файлов в outputFile. Каждая страница outputFile будет содержать две страницы: одна из первого входного файла, другая — из второго входного файла. Эти две страницы размещаются горизонтально.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::String &firstInputFile, const System::String &secondInputFile, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | const System::String\& | Первый входной файл. |
| secondInputFile | const System::String\& | Второй входной файл. |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |

### ReturnValue

boolean — True при успехе, иначе false.

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::String\&, const System::String\&, int32_t, int32_t) method


Создает N‑Up документ из firstInputFile в outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::String &inputFile, const System::String &outputFile, int32_t x, int32_t y)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь и имя входного pdf‑файла. |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |

### ReturnValue

boolean — True при успехе, иначе false.

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::String\&, const System::String\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&) method


Создает N‑Up документ из входного файла в outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::String &inputFile, const System::String &outputFile, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь и имя входного pdf‑файла. |
| outputFile | const System::String\& | Путь и имя выходного pdf‑файла. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы выходного pdf‑файла. |

### ReturnValue

boolean — True при успехе, иначе false.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::String\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создает N‑up документ и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::String &inputFile, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Путь к исходному файлу. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер [Page](../../../aspose.pdf/page/) в результирующем файле. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeNUp(const System::String\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Создает N‑up документ и сохраняет результат в HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeNUp(const System::String &inputFile, int32_t x, int32_t y, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Имя исходного файла. |
| x | int32_t | Количество столбцов. |
| y | int32_t | Количество строк. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
