---
title: "Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst method"
linktitle: "TrySplitFromFirst"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst method. Делит от начала до указанного места и сохраняет переднюю часть в выходном Stream в C++."
type: docs
weight: 7000
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## PdfFileEditor::TrySplitFromFirst(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Разделяет от начала до указанного места и сохраняет переднюю часть в выходной поток.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Исходный поток файла [Pdf](../../../aspose.pdf/). |
| location | int32_t | Точка разреза. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток выходного файла. |

### ReturnValue

True при успехе, иначе false.
## Примечания



Потоки НЕ закрываются после этой операции. Метод TrySplitFromFirst похож на метод SplitFromFirst, за исключением того, что метод TrySplitFromFirst не бросает исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TrySplitFromFirst(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Разделяет документ от начала до указанного места и сохраняет результат в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток исходного документа. |
| location | int32_t | Точка разреза. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором будет сохранён результат. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TrySplitFromFirst похож на метод SplitFromFirst, за исключением того, что метод TrySplitFromFirst не бросает исключение, если операция не удалась.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TrySplitFromFirst(const System::String\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Разделяет документ с первой страницы до места и сохраняет результат в объекты HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst(const System::String &inputFile, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Имя исходного файла. |
| location | int32_t | Точка разбиения. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объекты HttpResponse. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TrySplitFromFirst похож на метод SplitFromFirst, за исключением того, что метод TrySplitFromFirst не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TrySplitFromFirst(const System::String\&, int32_t, const System::String\&) method


Разделяет файл [Pdf](../../../aspose.pdf/) с первой страницы до указанного места и сохраняет переднюю часть как новый файл.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TrySplitFromFirst(const System::String &inputFile, int32_t location, const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | const System::String\& | Исходный файл [Pdf](../../../aspose.pdf/). |
| location | int32_t | Точка разреза. |
| outputFile | const System::String\& | Выводит файл [Pdf](../../../aspose.pdf/). |

### ReturnValue

True при успехе, иначе false.
## Примечания



Метод TrySplitFromFirst похож на метод SplitFromFirst, за исключением того, что метод TrySplitFromFirst не бросает исключение, если операция не удалась.
## См. также

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
