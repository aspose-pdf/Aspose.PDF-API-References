---
title: "Aspose::Pdf::Facades::PdfFileEditor::AddMargins method"
linktitle: "AddMargins"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::AddMargins method. Изменяет размер содержимого страницы и добавляет указанные поля. Поля задаются в единицах пространства по умолчанию в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/addmargins/
---
## PdfFileEditor::AddMargins(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в единицах пространства по умолчанию.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMargins(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий исходный документ. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будет сохранён результирующий документ. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) отступ. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) отступ. |
| topMargin | double | Верхний отступ. |
| bottomMargin | double | Нижний отступ. |

### ReturnValue

true, если операция была успешной.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddMargins(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в единицах пространства по умолчанию.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMargins(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const System::String\& | Путь к исходному документу. |
| destination | const System::String\& | Путь, по которому будет сохранён результирующий документ. |
| страницы | const System::ArrayPtr\<int32_t\>\& | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) отступ. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) отступ. |
| topMargin | double | Верхний отступ. |
| bottomMargin | double | Нижний отступ. |

### ReturnValue

true, если изменение размера прошло успешно.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
