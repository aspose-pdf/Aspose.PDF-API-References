---
title: Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks method
linktitle: ExtractBookmarks
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks method. Extracts bookmarks of all levels from the document in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## PdfBookmarkEditor::ExtractBookmarks() method


Extracts bookmarks of all levels from the document.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks()
```


### ReturnValue

The bookmarks collection of all bookmarks that exist in the document.

## See Also

* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(bool) method


Extracts bookmarks of all levels from the document.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(bool upperLevel)
```


| Parameter | Type | Description |
| --- | --- | --- |
| upperLevel | bool | If true, extracts only upper level bookmarks. Else, extracts all bookmarks recursively. |

### ReturnValue

List of extracted bookmarks.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>upperLevel</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If true, extracts only upper level bookmarks. Else, extracts all bookmarks recursively.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(System::String) method


Extracts the bookmarks with the specified title.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(System::String title)
```


| Parameter | Type | Description |
| --- | --- | --- |
| title | System::String | Extracted item title. |

### ReturnValue

[Bookmark](../../bookmark/) collection has items with the same title.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>title</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Extracted item title.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(System::SharedPtr\<Bookmark\>) method


Extracts the children of a bookmark with a title like in specified bookamrk.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(System::SharedPtr<Bookmark> bookmark)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | System::SharedPtr\<Bookmark\> | The specified bookamrk. |

### ReturnValue

[Bookmark](../../bookmark/) collection with child bookmarks.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>bookmark</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The specified bookamrk.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Bookmarks](../../bookmarks/)
* Class [Bookmark](../../bookmark/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
