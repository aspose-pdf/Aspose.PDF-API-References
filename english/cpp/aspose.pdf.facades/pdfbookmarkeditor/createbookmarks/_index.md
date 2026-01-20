---
title: Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks method
linktitle: CreateBookmarks
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks method. Creates bookmarks for all pages in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## PdfBookmarkEditor::CreateBookmarks() method


Creates bookmarks for all pages.

```cpp
void Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks()
```

## See Also

* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::CreateBookmarks(System::Drawing::Color, bool, bool) method


Create bookmarks for all pages with specified color and style (bold, italic).

```cpp
void Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks(System::Drawing::Color color, bool boldFlag, bool italicFlag)
```


| Parameter | Type | Description |
| --- | --- | --- |
| color | System::Drawing::Color | The color of title. |
| boldFlag | bool | The flag of bold attribution. |
| italicFlag | bool | The flag of italic attribution. |

## See Also

* Class [Color](../../../system.drawing/color/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::CreateBookmarks(System::SharedPtr\<Bookmark\>) method


Creates the specified bookmark in the document. The method can be used for forming nested bookmarks hierarchy.

```cpp
void Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks(System::SharedPtr<Bookmark> bookmark)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | System::SharedPtr\<Bookmark\> | The bookmark will be added to the document. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmark](../../bookmark/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
