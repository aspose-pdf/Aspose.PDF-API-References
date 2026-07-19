---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents метод"
linktitle: "TryResizeContents"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents method. Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля. Результат сохраняется в объект HttpResponse в C++."
type: docs
weight: 6900
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## PdfFileEditor::TryResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля. Результат сохраняется в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::SharedPtr\<System::IO::Stream\>\& | Поток исходного файла. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив страниц, которые нужно изменить по размеру. |
| параметры | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Параметры изменения размера. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором сохраняется результат. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Изменяет размер содержимого страниц документа.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::SharedPtr\<System::IO::Stream\>\& | Поток с исходным документом. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Поток с целевым документом. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив индексов страниц. |
| параметры | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Параметры изменения размера. |

### ReturnValue

Возвращает true, если успешно.
## Примечания



Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого задаётся в единицах пространства по умолчанию.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий исходный документ. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будет сохранён результирующий документ. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в единицах пространства по умолчанию. |
| newHeight | double | Новая высота содержимого страницы в единицах пространства по умолчанию. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не бросает исключение, если операция завершается неудачей.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля. Результат сохраняется в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::String &source, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::String\& | Путь к исходному файлу. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив страниц, которые нужно изменить по размеру. |
| параметры | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Параметры изменения размера. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором сохраняется результат. |

### ReturnValue

true, если операция завершилась успешно; иначе false.
## Примечания



Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не бросает исключение, если операция завершается неудачей.
## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::String\& | Путь к исходному документу. |
| destination | const System::String\& | Путь к целевому документу. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив индексов страниц (индекс страницы начинается с 1). |
| параметры | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Параметры изменения размера страницы. |

### ReturnValue

true, если изменение размера прошло успешно.
## Примечания



Метод TryResizeContents похож на метод ResizeContents, за исключением того, что метод TryResizeContents не бросает исключение, если операция завершается неудачей.
## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
