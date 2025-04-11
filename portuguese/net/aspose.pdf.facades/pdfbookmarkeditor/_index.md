---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfBookmarkEditor. Representa uma classe para trabalhar com marcadores de arquivos PDF, incluindo criar, modificar, exportar, importar e excluir
type: docs
weight: 4420
url: /pt/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## Classe PdfBookmarkEditor

Representa uma classe para trabalhar com os marcadores de arquivos PDF, incluindo criar, modificar, exportar, importar e excluir.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | Inicializa um novo objeto `PdfBookmarkEditor`. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | Inicializa um novo objeto `PdfBookmarkEditor` com base no *documento*. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa a fachada. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Desfaz o Aspose.Pdf.Document vinculado a uma fachada. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | Cria um marcador para a página especificada. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | Cria marcadores para as páginas especificadas. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | Cria marcadores para todas as páginas. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | Cria o marcador especificado no documento. O método pode ser usado para formar uma hierarquia de marcadores aninhados. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | Cria marcadores para todas as páginas com a cor e estilo especificados (negrito, itálico). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | Exclui todos os marcadores do documento PDF. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | Exclui o marcador do documento PDF. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | Exporta marcadores para o fluxo XML. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | Exporta marcadores para o arquivo XML. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | Extrai marcadores de todos os níveis do documento. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | Extrai os filhos de um marcador com um título como no marcador especificado. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | Extrai marcadores de todos os níveis do documento. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | Extrai os marcadores com o título especificado. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | Importa marcadores para o documento a partir do arquivo XML. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | Importa marcadores para o documento a partir do arquivo XML. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | Modifica o título do marcador de acordo com o título do marcador especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva o documento PDF no fluxo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva o documento PDF no arquivo especificado. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | Exporta marcadores para o arquivo HTML. |

### Veja Também

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)