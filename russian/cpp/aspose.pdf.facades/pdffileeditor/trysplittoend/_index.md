---
title: "Aspose::Pdf::Facades::PdfFileEditor::TrySplitToEnd method"
linktitle: "TrySplitToEnd"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TrySplitToEnd method. Разделяет с указанного места и сохраняет заднюю часть как новый поток файла в C++."
type: docs
weight: 7100
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## PdfFileEditor::TrySplitToEnd(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Разделяет от указанного места и сохраняет заднюю часть как новый поток файла.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitToEnd(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Исходный поток файла [Pdf](../../../aspose.pdf/). |
| location | int32_t | Позиция разделения. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Выходной [Pdf](../../../aspose.pdf/) файловый поток. |

### ReturnValue

True при успехе, иначе false.
## Примечания



Потоки НЕ закрываются после этой операции, если не указано CloseConcatedStreams. Метод TrySplitToEnd похож на метод SplitToEnd, за исключением того, что метод TrySplitToEnd не бросает исключение при неудаче операции.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TrySplitToEnd(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Разделяет с указанного места и сохраняет заднюю часть в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitToEnd(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток исходного документа. |
| location | int32_t | Точка разбиения. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TrySplitToEnd похож на метод SplitToEnd, за исключением того, что метод TrySplitToEnd не бросает исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TrySplitToEnd(const System::String\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Разделяет с указанного места и сохраняет заднюю часть в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitToEnd(const System::String &inputFile, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | имя исходного файла. |
| location | int32_t | Точка разбиения. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объекты HttpResponse. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TrySplitToEnd похож на метод SplitToEnd, за исключением того, что метод TrySplitToEnd не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TrySplitToEnd(const System::String\&, int32_t, const System::String\&) method


Разделяет от указанного места и сохраняет заднюю часть как новый файл.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitToEnd(const System::String &inputFile, int32_t location, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Исходный файл [Pdf](../../../aspose.pdf/). |
| location | int32_t | Позиция разделения. |
| outputFile | const System::String\& | Путь к выходному файлу [Pdf](../../../aspose.pdf/). |

### ReturnValue

True при успехе, иначе false.
## Примечания



Метод TrySplitToEnd похож на метод SplitToEnd, за исключением того, что метод TrySplitToEnd не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
