---
title: "Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks метод"
linktitle: "ExtractBookmarks"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks метод. Извлекает закладки всех уровней из документа на C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## PdfBookmarkEditor::ExtractBookmarks() method


Извлекает закладки всех уровней из документа.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks()
```


### ReturnValue

Коллекция закладок всех закладок, существующих в документе.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(bool) method


Извлекает закладки всех уровней из документа.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(bool upperLevel)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| upperLevel | bool | Если true, извлекает только закладки верхнего уровня. Иначе извлекает все закладки рекурсивно. |

### ReturnValue

Список извлечённых закладок.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(const System::SharedPtr\<Bookmark\>\&) method


Извлекает дочерние элементы закладки с заголовком, похожим на указанный.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(const System::SharedPtr<Bookmark> &bookmark)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| bookmark | const System::SharedPtr\<Bookmark\>\& | Указанная bookamrk. |

### ReturnValue

[Bookmark](../../bookmark/) collection with child bookmarks.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [Bookmark](../../bookmark/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(const System::String\&) method


Извлекает закладки с указанным заголовком.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(const System::String &title)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| title | const System::String\& | Заголовок извлечённого элемента. |

### ReturnValue

[Bookmark](../../bookmark/) collection has items with the same title.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [String](../../../system/string/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
