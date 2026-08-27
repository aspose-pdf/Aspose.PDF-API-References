---
title: "PdfBookmarkEditor"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет класс для работы с закладками PDF‑файла, включая создание, изменение, экспорт, импорт и удаление."
type: docs
weight: 180
url: /ru/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

Представляет класс для работы с закладками PDF‑файла, включая создание, изменение, экспорт, импорт и удаление.

Тип PdfBookmarkEditor раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfBookmarkEditor() | Инициализирует новый объект [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/) . |
| PdfBookmarkEditor(document) | Инициализирует новый экземпляр класса PdfBookmarkEditor |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(src_file) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_stream) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_doc) | Привязывает PDF-документ для редактирования. |
| save(dest_file) | Сохраняет документ PDF в указанный файл. |
| save(dest_stream) | Сохраняет документ PDF в указанный поток. |
| create_bookmarks() | Создает закладки для всех страниц. |
| create_bookmarks(bookmark) | Создает закладки для всех страниц. |
| create_bookmarks(color, bold_flag, italic_flag) | Создайте закладки для всех страниц с указанным цветом и стилем (жирный, курсив). |
| create_bookmark_of_page(bookmark_name, page_number) | Создаёт закладку для указанной страницы. |
| create_bookmark_of_page(bookmark_name, page_number) | Создаёт закладки для указанных страниц. |
| delete_bookmarks() | Удаляет все закладки PDF‑документа. |
| delete_bookmarks(title) | Удаляет закладку PDF‑документа. |
| extract_bookmarks() | Извлекает закладки всех уровней из документа. |
| extract_bookmarks(upper_level) | Извлекает закладки всех уровней из документа. |
| extract_bookmarks(title) | Извлекает закладки с указанным заголовком. |
| extract_bookmarks(bookmark) | Извлекает закладки всех уровней из документа. |
| export_bookmarks_to_xml(xml_file) | Экспортирует закладки в XML‑файл. |
| export_bookmarks_to_xml(stream) | Экспортирует закладки в XML‑поток. |
| import_bookmarks_with_xml(xml_file) | Импортирует закладки в документ из XML‑файла. |
| import_bookmarks_with_xml(stream) | Импортирует закладки в документ из XML‑файла. |
| close() | Освобождает любые ресурсы, связанные с текущим фасадом. |
| modify_bookmarks(s_title, d_title) | Изменяет заголовок закладки в соответствии с указанным заголовком закладки. |
| extract_bookmarks_to_html(pdf_file, css_file) | Экспортирует закладки в HTML‑файл. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | Экспортирует закладки в HTML‑файл. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

