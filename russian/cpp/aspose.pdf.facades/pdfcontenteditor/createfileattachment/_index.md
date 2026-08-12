---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment method"
linktitle: "CreateFileAttachment"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment method. Создаёт аннотацию вложения файла в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle, const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, int32_t, const System::String\&) method


Создаёт аннотацию вложения файла.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle rect, const System::String &contents, const System::SharedPtr<System::IO::Stream> &attachmentStream, const System::String &attachmentName, int32_t page, const System::String &name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник аннотации, определяющий её расположение на странице. |
| contents | const System::String\& | Содержимое аннотации. |
| attachmentStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток файла вложения. |
| attachmentName | const System::String\& | Имя вложения. |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана аннотация. |
| имя | const System::String\& | Имя значка будет использоваться при отображении аннотации. Это значение может быть: "Graph", "PushPin", "Paperclip", "Tag". |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle, const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, int32_t, const System::String\&, double) method


Создаёт аннотацию вложения файла.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle rect, const System::String &contents, const System::SharedPtr<System::IO::Stream> &attachmentStream, const System::String &attachmentName, int32_t page, const System::String &name, double opacity)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник аннотации, определяющий её расположение на странице. |
| contents | const System::String\& | Содержимое аннотации. |
| attachmentStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток файла вложения. |
| attachmentName | const System::String\& | Имя вложения. |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана аннотация. |
| имя | const System::String\& | Имя значка будет использоваться при отображении аннотации. Это значение может быть: "Graph", "PushPin", "Paperclip", "Tag". |
| непрозрачность | double | Непрозрачность значка от 0 до 1: 0 — полностью прозрачный, 1 — полностью непрозрачный. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&) method


Создаёт аннотацию вложения файла.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle rect, const System::String &contents, const System::String &filePath, int32_t page, const System::String &name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник аннотации, определяющий её расположение на странице. |
| contents | const System::String\& | Содержимое аннотации. |
| filePath | const System::String\& | Путь к файлу будет прикреплён. |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана аннотация. |
| имя | const System::String\& | Имя значка будет использоваться при отображении аннотации. Это значение может быть: "Graph", "PushPin", "Paperclip", "Tag". |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&, double) method


Создаёт аннотацию вложения файла.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateFileAttachment(System::Drawing::Rectangle rect, const System::String &contents, const System::String &filePath, int32_t page, const System::String &name, double opacity)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник аннотации, определяющий её расположение на странице. |
| contents | const System::String\& | Содержимое аннотации. |
| filePath | const System::String\& | Путь к файлу будет прикреплён. |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана аннотация. |
| имя | const System::String\& | Имя значка будет использоваться при отображении аннотации. Это значение может быть: "Graph", "PushPin", "Paperclip", "Tag". |
| непрозрачность | double | Непрозрачность значка от 0 до 1: 0 — полностью прозрачный, 1 — полностью непрозрачный. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
