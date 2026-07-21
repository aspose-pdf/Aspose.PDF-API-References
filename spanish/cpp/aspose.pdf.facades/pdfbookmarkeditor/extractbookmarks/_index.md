---
title: "Método Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks"
linktitle: "ExtractBookmarks"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks. Extrae los marcadores de todos los niveles del documento en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## PdfBookmarkEditor::ExtractBookmarks() method


Extrae los marcadores de todos los niveles del documento.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks()
```


### ReturnValue

La colección de marcadores de todos los marcadores que existen en el documento.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(bool) method


Extrae los marcadores de todos los niveles del documento.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(bool upperLevel)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| upperLevel | bool | Si es verdadero, extrae solo los marcadores de nivel superior. De lo contrario, extrae todos los marcadores recursivamente. |

### ReturnValue

Lista de marcadores extraídos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(const System::SharedPtr\<Bookmark\>\&) method


Extrae los hijos de un marcador con un título como en el marcador especificado bookamrk.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(const System::SharedPtr<Bookmark> &bookmark)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bookmark | const System::SharedPtr\<Bookmark\>\& | El marcador especificado. |

### ReturnValue

[Bookmark](../../bookmark/) collection with child bookmarks.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [Bookmark](../../bookmark/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::ExtractBookmarks(const System::String\&) method


Extrae los marcadores con el título especificado.

```cpp
System::SharedPtr<Bookmarks> Aspose::Pdf::Facades::PdfBookmarkEditor::ExtractBookmarks(const System::String &title)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| title | const System::String\& | Título del elemento extraído. |

### ReturnValue

[Bookmark](../../bookmark/) collection has items with the same title.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmarks](../../bookmarks/)
* Class [String](../../../system/string/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
