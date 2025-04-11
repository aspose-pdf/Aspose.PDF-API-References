---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfBookmarkEditor. Representa una clase para trabajar con los marcadores de archivos PDF, incluyendo crear, modificar, exportar, importar y eliminar.
type: docs
weight: 4420
url: /es/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## Clase PdfBookmarkEditor

Representa una clase para trabajar con los marcadores de archivos PDF, incluyendo crear, modificar, exportar, importar y eliminar.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | Inicializa un nuevo objeto `PdfBookmarkEditor`. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | Inicializa un nuevo objeto `PdfBookmarkEditor` basado en el *documento*. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene la fachada del documento en el que se está trabajando. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa la fachada. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Libera el Aspose.Pdf.Document vinculado con una fachada. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | Crea un marcador para la página especificada. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | Crea marcadores para las páginas especificadas. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | Crea marcadores para todas las páginas. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | Crea el marcador especificado en el documento. El método se puede usar para formar una jerarquía de marcadores anidados. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | Crea marcadores para todas las páginas con el color y estilo (negrita, cursiva) especificados. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | Elimina todos los marcadores del documento PDF. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | Elimina el marcador del documento PDF. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libera la fachada. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | Exporta marcadores a un flujo XML. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | Exporta marcadores a un archivo XML. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | Extrae marcadores de todos los niveles del documento. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | Extrae los hijos de un marcador con un título como en el marcador especificado. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | Extrae marcadores de todos los niveles del documento. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | Extrae los marcadores con el título especificado. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | Importa marcadores al documento desde un archivo XML. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | Importa marcadores al documento desde un archivo XML. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | Modifica el título del marcador de acuerdo con el título del marcador especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Guarda el documento PDF en el flujo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Guarda el documento PDF en el archivo especificado. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | Exporta marcadores a un archivo HTML. |

### Véase También

* clase [SaveableFacade](../saveablefacade/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../)