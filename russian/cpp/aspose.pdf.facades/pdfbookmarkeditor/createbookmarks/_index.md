---
title: "Метод Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks"
linktitle: "CreateBookmarks"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks. Создаёт закладки для всех страниц в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## PdfBookmarkEditor::CreateBookmarks() method


Создает закладки для всех страниц.

```cpp
void Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks()
```

## См. также

* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::CreateBookmarks(const System::SharedPtr\<Bookmark\>\&) method


Создает указанную закладку в документе. Этот метод можно использовать для формирования вложенной иерархии закладок.

```cpp
void Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks(const System::SharedPtr<Bookmark> &bookmark)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| bookmark | const System::SharedPtr\<Bookmark\>\& | Закладка будет добавлена в документ. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmark](../../bookmark/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::CreateBookmarks(System::Drawing::Color, bool, bool) method


Создает закладки для всех страниц с указанным цветом и стилем (жирный, курсив).

```cpp
void Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks(System::Drawing::Color color, bool boldFlag, bool italicFlag)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| color | System::Drawing::Color | Цвет заголовка. |
| boldFlag | bool | Флаг жирного оформления. |
| italicFlag | bool | Флаг курсивного оформления. |

## См. также

* Class [Color](../../../system.drawing/color/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
