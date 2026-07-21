---
title: "Método Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks"
linktitle: "CreateBookmarks"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks. Crea marcadores para todas las páginas en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## PdfBookmarkEditor::CreateBookmarks() method


Crea marcadores para todas las páginas.

```cpp
void Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks()
```

## Ver también

* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::CreateBookmarks(const System::SharedPtr\<Bookmark\>\&) method


Crea el marcador especificado en el documento. El método puede usarse para formar una jerarquía de marcadores anidados.

```cpp
void Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks(const System::SharedPtr<Bookmark> &bookmark)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bookmark | const System::SharedPtr\<Bookmark\>\& | El marcador será añadido al documento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bookmark](../../bookmark/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfBookmarkEditor::CreateBookmarks(System::Drawing::Color, bool, bool) method


Crea marcadores para todas las páginas con el color y estilo especificados (negrita, cursiva).

```cpp
void Aspose::Pdf::Facades::PdfBookmarkEditor::CreateBookmarks(System::Drawing::Color color, bool boldFlag, bool italicFlag)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | System::Drawing::Color | El color del título. |
| boldFlag | bool | La bandera de atributo en negrita. |
| italicFlag | bool | La bandera de atributo en cursiva. |

## Ver también

* Class [Color](../../../system.drawing/color/)
* Class [PdfBookmarkEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
