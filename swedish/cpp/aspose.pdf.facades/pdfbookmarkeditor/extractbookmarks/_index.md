---
title: "Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks-metod"
linktitle: "ExtractBookmarks"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks-metod. Extraherar bokmärken på alla nivåer från dokumentet i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## PdfBookmarkEditor::ExtractBookmarks() method


Extraherar bokmärken på alla nivåer från dokumentet.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks()
```


### ReturnValue

Bokmärkeskollektionen av alla bokmärken som finns i dokumentet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(bool) method


Extraherar bokmärken på alla nivåer från dokumentet.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(bool upperLevel)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| upperLevel | bool | Om true, extraherar endast bokmärken på översta nivån. Annars extraheras alla bokmärken rekursivt. |

### ReturnValue

Lista över extraherade bokmärken.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(const System::SharedPtr\<Bookmark\>\&) method


Extraherar underobjekten för ett bokmärke med en titel som i det angivna bokmärket.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(const System::SharedPtr<Bookmark> &bookmark)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bokmärke | const System::SharedPtr\<Bookmark\>\& | Den specificerade bookamrk. |

### ReturnValue

[Bookmark](../../bookmark/) collection with child bookmarks.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [Bookmark](../../bookmark/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(const System::String\&) method


Extraherar bokmärkena med den angivna titeln.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(const System::String &title)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| titel | const System::String\& | Extraherad objekttitel. |

### ReturnValue

[Bookmark](../../bookmark/) collection has items with the same title.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [String](../../../system/string/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
