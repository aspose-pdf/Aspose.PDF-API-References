---
title: "Метод Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate"
linktitle: "TryConcatenate"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate. Объединяет документы в C++."
type: docs
weight: 6300
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&, const System::SharedPtr\<Document\>\&) method


Объединяет документы.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::SharedPtr<Document>> &src, const System::SharedPtr<Document> &dest)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const System::ArrayPtr\<System::SharedPtr\<Document\>\>\& | Массив исходных документов. |
| dest | const System::SharedPtr\<Document\>\& | Документ назначения. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не бросает исключение, если операция не удалась.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Объединяет файлы.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Массив потоков для конкатенации. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будет сохранён результирующий файл. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не бросает исключение, если операция не удалась.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Объединяет файлы и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &inputStream, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Массив потоков, содержащих файлы для конкатенации. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект ответа/ |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не бросает исключение, если операция не удалась.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::String\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Объединяет файлы и сохраняет reslt в объект HttpResposnse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::String> &inputFiles, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | const System::ArrayPtr\<System::String\>\& | Массив файлов для конкатенации. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект ответа. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не бросает исключение, если операция не удалась.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::String\>\&, const System::String\&) method


Объединяет файлы в один файл.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::String> &inputFiles, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | const System::ArrayPtr\<System::String\>\& | Массив файлов для конкатенации. |
| outputFile | const System::String\& | Имя выходного файла. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не бросает исключение, если операция не удалась.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Объединяет два документа [Pdf](../../../aspose.pdf/) в новый документ [Pdf](../../../aspose.pdf/), размещая страницы попеременно и заполняя пустые места пустыми страницами. Например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов [Pdf](../../../aspose.pdf/) создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::SharedPtr<System::IO::Stream> &firstInputStream, const System::SharedPtr<System::IO::Stream> &secInputStream, const System::SharedPtr<System::IO::Stream> &blankPageStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | const System::SharedPtr\<System::IO::Stream\>\& | Первый поток [Pdf](../../../aspose.pdf/). |
| secInputStream | const System::SharedPtr\<System::IO::Stream\>\& | Второй поток [Pdf](../../../aspose.pdf/). |
| blankPageStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток [Pdf](../../../aspose.pdf/) с пустой страницей. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выводит [Pdf](../../../aspose.pdf/) поток. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не бросает исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::String\&, const System::String\&, const System::String\&, const System::String\&) method


Объединяет два документа [Pdf](../../../aspose.pdf/) в новый документ [Pdf](../../../aspose.pdf/), размещая страницы попеременно и заполняя пустые места пустыми страницами. Например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов [Pdf](../../../aspose.pdf/) создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::String &firstInputFile, const System::String &secInputFile, const System::String &blankPageFile, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | const System::String\& | Первый файл. |
| secInputFile | const System::String\& | Второй файл. |
| blankPageFile | const System::String\& | PDF файл с пустой страницей. |
| outputFile | const System::String\& | Файл результата. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::String\&, const System::String\&, const System::String\&) method


Объединяет два файла.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::String &firstInputFile, const System::String &secInputFile, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | const System::String\& | Первый файл для объединения. |
| secInputFile | const System::String\& | Второй файл для объединения. |
| outputFile | const System::String\& | Выходной файл. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryConcatenate похож на метод Concatenate, за исключением того, что метод TryConcatenate не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
