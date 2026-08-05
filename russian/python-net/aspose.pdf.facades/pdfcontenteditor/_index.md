---
title: "PdfContentEditor"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет класс для редактирования содержимого PDF‑файла."
type: docs
weight: 190
url: /ru/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

Представляет класс для редактирования содержимого PDF‑файла.

Тип PdfContentEditor раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfContentEditor() | Конструктор объекта PdfContentEditor. |
| PdfContentEditor(document) | Инициализирует новый экземпляр класса PdfContentEditor |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
| text_search_options | Получает или задает параметры поиска текста. |
| text_edit_options | Получает или задает параметры редактирования текста. |
| text_replace_options | Получает или задает параметры замены текста. |
| replace_text_strategy | Набор параметров для операции замены текста |
| DOCUMENT_OPEN | Тип события документа. Открывает документ. |
| DOCUMENT_CLOSE | Тип события документа. Закрывает документ. |
| DOCUMENT_WILL_SAVE | Тип события документа. Выполняет действие перед сохранением. |
| DOCUMENT_SAVED | Тип события документа. Выполняет действие после сохранения. |
| DOCUMENT_WILL_PRINT | Тип события документа. Выполняет действие перед печатью. |
| DOCUMENT_PRINTED | Тип события документа. Выполняет действие после печати. |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(input_file) | Привязывает PDF‑файл для редактирования. |
| bind_pdf(input_stream) | Привязывает поток PDF для редактирования. |
| bind_pdf(src_doc) | Привязывает PDF-документ для редактирования. |
| save(dest_file) | Сохраняет документ PDF в указанный файл. |
| save(dest_stream) | Сохраняет документ PDF в указанный поток. |
| create_web_link(rect, url, original_page, clr) | Создаёт веб‑ссылку в PDF‑документе. |
| create_web_link(rect, url, original_page) | Создаёт веб‑ссылку в PDF‑документе. |
| create_local_link(rect, des_page, original_page, clr) | Создаёт локальную ссылку в PDF‑документе. |
| create_local_link(rect, des_page, original_page) | Создаёт локальную ссылку в PDF‑документе. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | Создаёт ссылку на страницу другого PDF‑документа. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | Создаёт ссылку на страницу другого PDF‑документа. |
| create_application_link(rect, application, page, clr) | Создаёт ссылку для запуска приложения в PDF‑документе. |
| create_application_link(rect, application, page) | Создаёт ссылку для запуска приложения в PDF‑документе. |
| create_file_attachment(rect, contents, file_path, page, name) | Создаёт аннотацию вложения файла. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | Создаёт аннотацию вложения файла. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | Создаёт аннотацию вложения файла. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | Создаёт аннотацию вложения файла. |
| add_document_attachment(file_attachment_path, description) | Добавляет вложение документа без аннотации. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | Добавляет вложение документа без аннотации. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | Создаёт аннотацию штамп. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | Создаёт аннотацию штамп. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | Создаёт аннотацию штамп. |
| delete_image(page_number, index) | Удаляет указанные изображения на указанной странице. |
| delete_image() | Удаляет указанные изображения на указанной странице. |
| replace_text(src_string, the_page, dest_string, text_state) | Заменяет текст в PDF‑файле на указанной странице. Объект [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (семейство шрифта, цвет) может быть указан для заменяемого текста. |
| replace_text(src_string, dest_string) | Заменяет текст в PDF‑файле на указанной странице. Объект [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (семейство шрифта, цвет) может быть указан для заменяемого текста. |
| replace_text(src_string, the_page, dest_string) | Заменяет текст в PDF‑файле на указанной странице. Объект [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (семейство шрифта, цвет) может быть указан для заменяемого текста. |
| replace_text(src_string, dest_string, text_state) | Заменяет текст в PDF‑файле на указанной странице. Объект [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (семейство шрифта, цвет) может быть указан для заменяемого текста. |
| replace_text(src_string, dest_string, font_size) | Заменяет текст в PDF‑файле на указанной странице. Объект [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (семейство шрифта, цвет) может быть указан для заменяемого текста. |
| delete_stamp_by_ids(stamp_ids) | Удаляет штампы с указанными идентификаторами со всех страниц документа. |
| delete_stamp_by_ids(page_number, stamp_ids) | Удаляет штампы с указанными идентификаторами со всех страниц документа. |
| delete_stamp_by_id(page_number, stamp_id) | Удаляет штампы с указанными идентификаторами со всех страниц документа. |
| delete_stamp_by_id(stamp_id) | Удаляет штампы с указанными идентификаторами со всех страниц документа. |
| close() | Закрывает открытый документ. |
| extract_link() | Извлекает коллекцию экземпляров Link, содержащихся в PDF‑документе. |
| create_java_script_link(code, rect, original_page, color) | Создаёт ссылку на JavaScript в PDF‑документе. |
| create_text(rect, title, contents, open, icon, page) | Создаёт текстовую аннотацию в PDF‑документе |
| create_free_text(rect, contents, page) | Создаёт аннотацию свободного текста в PDF‑документе |
| create_markup(rect, contents, type, page, clr) | Создаёт разметочную аннотацию в PDF‑документе. |
| create_popup(rect, contents, open, page) | Создаёт всплывающую аннотацию в PDF‑документе. |
| delete_attachments() | Удаляет все вложения в PDF‑документе. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | Создаёт аннотацию линии. |
| create_square_circle(rect, contents, clr, square, page, border_width) | Создаёт аннотацию квадрат‑круг. |
| draw_curve(line_info, page, annot_rect, annot_contents) | Создаёт аннотацию кривой. |
| create_polygon(line_info, page, annot_rect, annot_contents) | Создаёт аннотацию многоугольника. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | Создаёт аннотацию полилинии. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | Создаёт аннотацию каретки. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | Создаёт закладку с указанным действием. |
| add_document_additional_action(event_type, code) | Добавляет дополнительное действие для события документа. |
| remove_document_open_action() | Удаляет действие открытия из документа. Эта операция полезна при объединении нескольких документов, использующих явное действие 'GoTo' при запуске. |
| change_viewer_preference(viewer_attribution) | Изменяет предпочтения просмотра. |
| get_viewer_preference() | Возвращает предпочтения просмотра. |
| replace_image(page_number, index, image_file) | Заменяет указанное изображение на указанной странице PDF‑документа другим изображением. |
| create_movie(rect, file_path, page) | Создает аннотации фильма. |
| create_sound(rect, file_path, name, page, rate) | Создает звуковые аннотации. |
| delete_stamp(page_number, index) | Удаляет несколько штампов на указанной странице по индексам штампов. |
| hide_stamp_by_id(page_number, stamp_id) | Скрывает штамп. После скрытия видимость штампа может быть восстановлена методом ShowStampById. |
| show_stamp_by_id(page_number, stamp_id) | Отображает штамп, скрытый методом HiddenStampById. |
| move_stamp_by_id(page_number, stamp_id, x, y) | Изменяет позицию штампа на странице. |
| move_stamp(page_number, stamp_index, x, y) | Изменяет позицию штампа на странице. |
| get_stamps(page_number) | Возвращает массив штампов на странице. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

