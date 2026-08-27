---
title: "PdfFileMend"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет класс для добавления текста и изображений на страницы существующего PDF‑документа."
type: docs
weight: 280
url: /ru/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

Представляет класс для добавления текста и изображений на страницы существующего PDF‑документа.

Тип PdfFileMend раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfFileMend() | Конструктор. |
| PdfFileMend(input_file_name, output_file_name) | Инициализирует новый экземпляр класса PdfFileMend |
| PdfFileMend(input_stream, output_stream) | Инициализирует новый экземпляр класса PdfFileMend |
| PdfFileMend(document) | Инициализирует новый экземпляр класса PdfFileMend |
| PdfFileMend(document, output_file_name) | Инициализирует новый экземпляр класса PdfFileMend |
| PdfFileMend(document, dest_stream) | Инициализирует новый экземпляр класса PdfFileMend |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
| input_stream | Устанавливает входной поток. |
| output_stream | Устанавливает выходной поток. |
| input_file | Устанавливает входной файл. |
| output_file | Устанавливает выходной файл. |
| wrap_mode | Устанавливает или получает алгоритм переноса слов. См. WordWrapMode и IsWordWrap. |
| text_positioning_mode | Устанавливает или получает стратегию позиционирования текста. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            По умолчанию режим — Legacy. |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(src_file) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_stream) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_doc) | Привязывает PDF-документ для редактирования. |
| save(dest_file) | Сохраняет документ PDF в указанный файл. |
| save(dest_stream) | Сохраняет документ PDF в указанный поток. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Добавляет изображение на указанную страницу PDF‑документа в заданных координатах. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Добавляет изображение на указанную страницу PDF‑документа в заданных координатах. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Добавляет изображение на указанные страницы PDF‑документа в заданных координатах. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Добавляет изображение на указанные страницы PDF‑документа в заданных координатах. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Добавляет изображение на указанную страницу PDF‑документа в заданных координатах. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Добавляет изображение на указанную страницу PDF‑документа в заданных координатах. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Добавляет изображение на указанные страницы PDF‑документа в заданных координатах. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Добавляет изображение на указанные страницы PDF‑документа в заданных координатах. |
| add_text(text, page_num, lower_left_x, lower_left_y) | Не реализовано. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Не реализовано. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Не реализовано. |
| close() | Закрывает объект PdfFileMend. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

