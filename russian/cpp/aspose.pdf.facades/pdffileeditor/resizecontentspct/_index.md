---
title: "Метод Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct"
linktitle: "ResizeContentsPct"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct. Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в процентах в C++."
type: docs
weight: 3600
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## PdfFileEditor::ResizeContentsPct(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого задаётся в процентах.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий исходный документ. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будет сохранён результирующий документ. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в процентах. |
| newHeight | double | Новая высота содержимого страницы в процентах. |

### ReturnValue

true, если изменение размера выполнено успешно.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContentsPct(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого задаётся в процентах.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::String\& | Путь к исходному документу. |
| destination | const System::String\& | Путь, по которому будет сохранён результирующий документ. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в процентах. |
| newHeight | double | Новая высота содержимого страницы в процентах. |

### ReturnValue

true, если изменение размера прошло успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
