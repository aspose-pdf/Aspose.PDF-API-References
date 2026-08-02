---
title: "Класс PdfBookmarkEditor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Facades.PdfBookmarkEditor class. Представляет класс для работы с закладками PDF‑файлов, включая создание, изменение, экспорт, импорт и удаление."
type: docs
weight: 4540
url: /ru/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class

Представляет класс для работы с закладками PDF‑файла, включая создание, изменение, экспорт, импорт и удаление.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | Инициализирует новый объект `PdfBookmarkEditor`. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | Инициализирует новый объект `PdfBookmarkEditor` на основе *document*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Освобождает Aspose.Pdf.Document, связанный с фасадом. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | Создает закладку для указанной page. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | Создает закладки для указанных pages. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | Создает закладки для всех pages. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | Создает указанную закладку в document. Этот метод можно использовать для формирования иерархии вложенных закладок. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | Создайте закладки для всех pages с указанным цветом и стилем (жирный, курсив). |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | Удаляет все закладки PDF document. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | Удаляет закладку PDF document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | Экспортирует закладки в поток XML. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | Экспортирует закладки в файл XML. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | Извлекает закладки всех уровней из document. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | Извлекает дочерние элементы закладки с заголовком, аналогичным указанной закладке. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | Извлекает закладки всех уровней из document. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | Извлекает закладки с указанным заголовком. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | Импортирует закладки в document из файла XML. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | Импортирует закладки в document из файла XML. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | Изменяет заголовок закладки в соответствии с указанным заголовком закладки. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Сохраняет PDF‑документ в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Сохраняет PDF‑документ в указанный файл. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | Экспортирует закладки в файл HTML. |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


