---
title: "Aspose::Pdf::Facades::PdfFileEditor::ResizeContents method"
linktitle: "ResizeContents"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::ResizeContents method. Изменяет размер страниц документа. Пустые поля добавляются вокруг уменьшенной страницы в C++."
type: docs
weight: 3500
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## PdfFileEditor::ResizeContents(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Изменяет размер страниц документа. Пустые поля добавляются вокруг уменьшенной страницы.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<Document> &source, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::SharedPtr\<Document\>\& | Исходный документ. |
| параметры | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Параметры изменения размера. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<Document\>\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Изменяет размер страниц документа. Пустые поля добавляются вокруг уменьшенной страницы.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<Document> &source, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::SharedPtr\<Document\>\& | Исходный документ. |
| страницы | System::ArrayPtr\<int32_t\> | Список индексов страниц. |
| параметры | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Параметры изменения размера. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого задаётся в единицах пространства по умолчанию.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий исходный документ. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будет сохранён результирующий документ. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в единицах пространства по умолчанию. |
| newHeight | double | Новая высота содержимого страницы в единицах пространства по умолчанию. |

### ReturnValue

True, если изменение размера прошло успешно.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Изменяет размер содержимого страниц документа.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::SharedPtr\<System::IO::Stream\>\& | Поток с исходным документом. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Поток с целевым документом. |
| страницы | System::ArrayPtr\<int32_t\> | Массив индексов страниц. |
| параметры | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Параметры изменения размера. |

### ReturnValue

Возвращает true, если успешно.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля. Результат сохраняется в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<System::IO::Stream> &source, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::SharedPtr\<System::IO::Stream\>\& | Поток исходного файла. |
| страницы | System::ArrayPtr\<int32_t\> | Массив страниц, которые нужно изменить по размеру. |
| параметры | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Параметры изменения размера. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором сохраняется результат. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого задаётся в единицах пространства по умолчанию.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::String\& | Путь к исходному документу. |
| destination | const System::String\& | Путь, по которому будет сохранён результирующий документ. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в единицах пространства по умолчанию. |
| newHeight | double | Новая высота содержимого страницы в единицах пространства по умолчанию. |

### ReturnValue

true, если изменение размера прошло успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::String\&, const System::String\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::String &source, const System::String &destination, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::String\& | Путь к исходному документу. |
| destination | const System::String\& | Путь к целевому документу. |
| страницы | System::ArrayPtr\<int32_t\> | Массив индексов страниц (индекс страницы начинается с 1). |
| параметры | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Параметры изменения размера страницы. |

### ReturnValue

true, если изменение размера прошло успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::String\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля. Результат сохраняется в объект HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::String &source, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::String\& | Путь к исходному файлу. |
| страницы | System::ArrayPtr\<int32_t\> | Массив страниц, которые нужно изменить по размеру. |
| параметры | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Параметры изменения размера. |
| ответ | const System::SharedPtr\<System::Web::HttpResponse\>\& | Объект HttpResponse, в котором сохраняется результат. |

### ReturnValue

True, если операция завершилась успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
