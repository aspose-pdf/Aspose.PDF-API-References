---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfBookmarkEditor. Représente une classe pour travailler avec les signets des fichiers PDF, y compris créer, modifier, exporter, importer et supprimer.
type: docs
weight: 4420
url: /fr/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## Classe PdfBookmarkEditor

Représente une classe pour travailler avec les signets des fichiers PDF, y compris créer, modifier, exporter, importer et supprimer.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | Initialise un nouvel objet `PdfBookmarkEditor`. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | Initialise un nouvel objet `PdfBookmarkEditor` sur la base du *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur lequel elle travaille. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialise la façade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Dispose du document Aspose.Pdf lié à une façade. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | Crée un signet pour la page spécifiée. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | Crée des signets pour les pages spécifiées. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | Crée des signets pour toutes les pages. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | Crée le signet spécifié dans le document. La méthode peut être utilisée pour former une hiérarchie de signets imbriqués. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | Crée des signets pour toutes les pages avec la couleur et le style spécifiés (gras, italique). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | Supprime tous les signets du document PDF. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | Supprime le signet du document PDF. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Dispose de la façade. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | Exporte les signets vers un flux XML. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | Exporte les signets vers un fichier XML. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | Extrait les signets de tous les niveaux du document. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | Extrait les enfants d'un signet avec un titre comme dans le signet spécifié. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | Extrait les signets de tous les niveaux du document. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | Extrait les signets avec le titre spécifié. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | Importe des signets dans le document à partir d'un fichier XML. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | Importe des signets dans le document à partir d'un fichier XML. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | Modifie le titre du signet selon le titre de signet spécifié. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Enregistre le document PDF dans le flux spécifié. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Enregistre le document PDF dans le fichier spécifié. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | Exporte les signets vers un fichier HTML. |

### Voir aussi

* classe [SaveableFacade](../saveablefacade/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)