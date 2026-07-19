---
title: "Aspose::Pdf::Facades::PdfBookmarkEditor класс"
linktitle: "PdfBookmarkEditor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfBookmarkEditor класс. Представляет класс для работы с закладками PDF‑файла, включая создание, изменение, экспорт, импорт и удаление в C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class


Представляет класс для работы с закладками PDF‑файла, включая создание, изменение, экспорт, импорт и удаление.

```cpp
class PdfBookmarkEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(const System::String\&, int32_t) | Создает закладку для указанной страницы. |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<int32_t\>\&) | Создает закладки для указанных страниц. |
| [CreateBookmarks](./createbookmarks/)() | Создает закладки для всех страниц. |
| [CreateBookmarks](./createbookmarks/)(const System::SharedPtr\<Bookmark\>\&) | Создает указанную закладку в документе. Этот метод можно использовать для формирования вложенной иерархии закладок. |
| [CreateBookmarks](./createbookmarks/)(System::Drawing::Color, bool, bool) | Создает закладки для всех страниц с указанным цветом и стилем (жирный, курсив). |
| [DeleteBookmarks](./deletebookmarks/)() | Удаляет все закладки PDF‑документа. |
| [DeleteBookmarks](./deletebookmarks/)(const System::String\&) | Удаляет закладку PDF‑документа. |
| static [ExportBookmarksToHtml](./exportbookmarkstohtml/)(const System::String\&, const System::String\&) | Экспортирует закладки в HTML‑файл. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(const System::String\&) | Экспортирует закладки в XML‑файл. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Экспортирует закладки в XML‑поток. |
| [ExtractBookmarks](./extractbookmarks/)() | Извлекает закладки всех уровней из документа. |
| [ExtractBookmarks](./extractbookmarks/)(bool) | Извлекает закладки всех уровней из документа. |
| [ExtractBookmarks](./extractbookmarks/)(const System::String\&) | Извлекает закладки с указанным заголовком. |
| [ExtractBookmarks](./extractbookmarks/)(const System::SharedPtr\<Bookmark\>\&) | Извлекает дочерние элементы закладки с заголовком, похожим на указанный. |
| [ExtractBookmarksToHTML](./extractbookmarkstohtml/)(const System::String\&, const System::String\&) | Экспортирует закладки в HTML‑файл. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(const System::String\&) | Импортирует закладки в документ из XML‑файла. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Импортирует закладки в документ из XML‑файла. |
| [ModifyBookmarks](./modifybookmarks/)(const System::String\&, const System::String\&) | Изменяет заголовок закладки в соответствии с указанным заголовком закладки. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/)() | Инициализирует новый объект [PdfBookmarkEditor](./). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfBookmarkEditor](./) на основе *document*. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
