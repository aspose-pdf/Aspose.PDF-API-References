---
title: Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks method
linktitle: ExtractBookmarks
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks method. Extracts bookmarks of all levels from the document in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## PdfBookmarkEditor::ExtractBookmarks() method


Extracts bookmarks of all levels from the document.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks()
```


### ReturnValue

The bookmarks collection of all bookmarks that exist in the document.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(bool) method


Extracts bookmarks of all levels from the document.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(bool upperLevel)
```


| Parameter | Type | Description |
| --- | --- | --- |
| upperLevel | bool | If true, extracts only upper level bookmarks. Else, extracts all bookmarks recursively. |

### ReturnValue

List of extracted bookmarks.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(System::SharedPtr\<Bookmark\>) method


Extracts the children of a bookmark with a title like in specified bookamrk.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(System::SharedPtr<Bookmark> bookmark)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | System::SharedPtr\<Bookmark\> | The specified bookamrk. |

### ReturnValue

[Bookmark](../../bookmark/) collection with child bookmarks.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [Bookmark](../../bookmark/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(System::String) method


Extracts the bookmarks with the specified title.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(System::String title)
```


| Parameter | Type | Description |
| --- | --- | --- |
| title | System::String | Extracted item title. |

### ReturnValue

[Bookmark](../../bookmark/) collection has items with the same title.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [String](../../../system/string/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
