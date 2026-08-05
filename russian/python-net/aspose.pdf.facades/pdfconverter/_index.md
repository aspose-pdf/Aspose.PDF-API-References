---
title: "PdfConverter"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет класс для преобразования каждой страницы PDF‑файла в изображения, поддерживая BMP, JPEG, PNG и TIFF.<br/>            Поддерживаемый контент в PDF: изображения, формы, комментарии."
type: docs
weight: 200
url: /ru/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

Представляет класс для преобразования каждой страницы pdf‑файла в изображения, сейчас поддерживает BMP, JPEG, PNG и TIFF.<br/>            Поддерживаемое содержимое в pdf: изображения, формы, комментарии.

Тип PdfConverter раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfConverter() | Инициализирует новый объект [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/). |
| PdfConverter(document) | Инициализирует новый экземпляр класса PdfConverter |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
| coordinate_type | Получает или задает тип координат страницы (Media/Crop коробки). Значение CropBox используется по умолчанию. |
| show_hidden_areas | Получает или задает флаг, контролирующий видимость скрытых областей на странице. |
| rendering_options | Получает или задает параметры рендеринга. |
| form_presentation_mode | Получает или задает режим представления формы. |
| resolution | Получает или задаёт разрешение при конвертации. Чем выше разрешение, тем медленнее скорость конвертации. Значение по умолчанию — 150. |
| start_page | Получает или задает начальную позицию, которую вы хотите преобразовать. Минимальное значение — 1. |
| end_page | Получает или задает конечную позицию, которую вы хотите преобразовать. |
| password | Получает или задает пароль владельца документа OwnerPassword. |
| user_password | Получает или задает пароль пользователя документа UserPassword. |
| page_count | Получает количество страниц. |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(input_file) | Привязывает PDF‑файл для преобразования. |
| bind_pdf(input_stream) | Привязывает поток PDF для преобразования. |
| bind_pdf(src_doc) | Инициализирует фасад. |
| save_as_tiff(output_file) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_file, compression_type) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_file, image_width, image_height) | Преобразует каждую страницу PDF‑документа в изображения с заданными размерами и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_file, page_size) | Преобразует каждую страницу PDF‑документа в изображения с размером страницы и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_file, page_size, settings) | Преобразует каждую страницу PDF‑документа в изображения с размером страницы и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | Преобразует каждую страницу PDF‑документа в изображения с заданными размерами и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_file, image_width, image_height, settings) | Преобразует каждую страницу PDF‑документа в изображения с заданными размерами и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | Преобразует каждую страницу PDF‑документа в изображения с заданными размерами и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_stream) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| save_as_tiff(output_stream, compression_type) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_stream, page_size) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| save_as_tiff(output_stream, page_size, settings) | Преобразует каждую страницу PDF‑документа в изображения с размером страницы и сохраняет изображения в один поток TIFF. |
| save_as_tiff(output_stream, image_width, image_height) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет изображения в один поток TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет изображения в один поток TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет изображения в один поток TIFF. |
| save_as_tiff(output_file, settings) | Преобразует каждую страницу PDF‑документа в изображения с размером страницы и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_file, settings, converter) | Преобразует каждую страницу PDF‑документа в изображения с заданными размерами и сохраняет их в один TIFF‑файл. |
| save_as_tiff(output_stream, settings) | Преобразует каждую страницу PDF‑документа в изображения с размером страницы и сохраняет изображения в один поток TIFF. |
| save_as_tiff(output_stream, settings, converter) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет изображения в один поток TIFF. |
| save_as_tiff_class_f(output_file, image_width, image_height) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет изображения в один файл TIFF ClassF. |
| save_as_tiff_class_f(output_file, page_size) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет изображения в один файл TIFF ClassF. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| save_as_tiff_class_f(output_stream, page_size) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| save_as_tiff_class_f(output_file) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет изображения в один файл TIFF ClassF. |
| save_as_tiff_class_f(output_stream) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| get_next_image(output_file) | Сохраняет изображение в файл с форматом изображения по умолчанию — JPEG. |
| get_next_image(output_file, page_size) | Сохраняет изображение в файл с указанным размером страницы и форматом изображения по умолчанию — JPEG. |
| get_next_image(output_file, format) | Сохраняет изображение в файл с указанным форматом изображения. |
| get_next_image(output_file, page_size, format) | Сохраняет изображение в файл с заданным размером страницы и форматом изображения. |
| get_next_image(output_stream) | Сохраняет изображение в поток с форматом изображения по умолчанию — jpeg. |
| get_next_image(output_stream, page_size) | Сохраняет изображение в поток с указанным размером страницы. |
| get_next_image(output_stream, format) | Сохраняет изображение в поток с указанным форматом изображения. |
| get_next_image(output_stream, page_size, format) | Сохраняет изображение в поток с указанным размером страницы. |
| get_next_image(output_file, format, image_width, image_height, quality) | Сохраняет изображение в файл с указанным форматом изображения, размерами и качеством. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Сохраняет изображение в поток с данным форматом изображения, размерами и качеством. |
| get_next_image(output_file, format, image_width, image_height, quality) | Сохраняет изображение в файл с данным форматом изображения, размером изображения и качеством. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Сохраняет изображение в поток с данным форматом изображения, размером и качеством. |
| get_next_image(output_file, format, image_width, image_height) | Сохраняет изображение в файл с указанным форматом изображения, размерами и качеством. |
| get_next_image(output_stream, format, image_width, image_height) | Сохраняет изображение в поток с данным форматом изображения, размерами и качеством. |
| get_next_image(output_stream, format, quality) | Сохраняет изображение в поток с данным форматом изображения, размерами и качеством. |
| get_next_image(output_stream, page_size, format, quality) | Сохраняет изображение в поток с указанным размером страницы, форматом изображения и качеством. |
| get_next_image(output_file, format, quality) | Сохраняет изображение в файл с указанным форматом изображения, размерами и качеством. |
| get_next_image(output_file, page_size, format, quality) | Сохраняет изображение в файл с указанным размером страницы, форматом изображения и качеством. |
| close() | Закрывает экземпляр PdfConverter и освобождает ресурсы. |
| do_convert() | Выполняет некоторые начальные действия для преобразования PDF‑документа в изображения. |
| has_next_image() | Указывает, содержит ли pdf‑файл больше изображений или нет. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | None |
| merge_images_as_tiff(input_images_streams) | Объединяет список потоков TIFF в один многокадровый поток TIFF. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

