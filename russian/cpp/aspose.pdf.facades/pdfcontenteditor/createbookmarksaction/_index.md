---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction method"
linktitle: "CreateBookmarksAction"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction method. Создаёт закладку с указанным действием в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor::CreateBookmarksAction method


Создаёт закладку с указанным действием.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction(const System::String &title, System::Drawing::Color color, bool boldFlag, bool italicFlag, const System::String &file, const System::String &actionType, const System::String &destination)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| title | const System::String\& | Заголовок закладки. |
| color | System::Drawing::Color | Цвет заголовка закладки. |
| boldFlag | bool | Флаг жирного оформления. |
| italicFlag | bool | Флаг курсивного оформления. |
| file | const System::String\& | Другой файл или приложение, требуемое, когда тип действия "GoToR" или "Launch". |
| actionType | const System::String\& | Тип действия. Значение может быть: "GoToR", "Launch", "GoTo", "URI". |
| destination | const System::String\& | Локальное назначение, удалённое назначение или URL. |

## См. также

* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
