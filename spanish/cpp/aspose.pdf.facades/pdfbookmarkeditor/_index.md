---
title: "Aspose::Pdf::Facades::PdfBookmarkEditor clase"
linktitle: "PdfBookmarkEditor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfBookmarkEditor clase. Representa una clase para trabajar con los marcadores del PDF file''s incluyendo crear, modificar, exportar, importar y eliminar en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class


Representa una clase para trabajar con los marcadores del archivo PDF, incluyendo crear, modificar, exportar, importar y eliminar.

```cpp
class PdfBookmarkEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(const System::String\&, int32_t) | Crea un marcador para la página especificada. |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<int32_t\>\&) | Crea marcadores para las páginas especificadas. |
| [CreateBookmarks](./createbookmarks/)() | Crea marcadores para todas las páginas. |
| [CreateBookmarks](./createbookmarks/)(const System::SharedPtr\<Bookmark\>\&) | Crea el marcador especificado en el documento. El método puede usarse para formar una jerarquía de marcadores anidados. |
| [CreateBookmarks](./createbookmarks/)(System::Drawing::Color, bool, bool) | Crea marcadores para todas las páginas con el color y estilo especificados (negrita, cursiva). |
| [DeleteBookmarks](./deletebookmarks/)() | Elimina todos los marcadores del documento PDF. |
| [DeleteBookmarks](./deletebookmarks/)(const System::String\&) | Elimina el marcador del documento PDF. |
| static [ExportBookmarksToHtml](./exportbookmarkstohtml/)(const System::String\&, const System::String\&) | Exporta los marcadores a un archivo HTML. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(const System::String\&) | Exporta los marcadores a un archivo XML. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporta los marcadores a un flujo XML. |
| [ExtractBookmarks](./extractbookmarks/)() | Extrae los marcadores de todos los niveles del documento. |
| [ExtractBookmarks](./extractbookmarks/)(bool) | Extrae los marcadores de todos los niveles del documento. |
| [ExtractBookmarks](./extractbookmarks/)(const System::String\&) | Extrae los marcadores con el título especificado. |
| [ExtractBookmarks](./extractbookmarks/)(const System::SharedPtr\<Bookmark\>\&) | Extrae los hijos de un marcador con un título como en el marcador especificado bookamrk. |
| [ExtractBookmarksToHTML](./extractbookmarkstohtml/)(const System::String\&, const System::String\&) | Exporta los marcadores a un archivo HTML. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(const System::String\&) | Importa los marcadores al documento desde un archivo XML. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importa los marcadores al documento desde un archivo XML. |
| [ModifyBookmarks](./modifybookmarks/)(const System::String\&, const System::String\&) | Modifica el título del marcador según el título del marcador especificado. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/)() | Inicializa un nuevo objeto [PdfBookmarkEditor](./). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfBookmarkEditor](./) basado en el *document*. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
