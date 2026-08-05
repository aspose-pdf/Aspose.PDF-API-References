---
title: "PdfFileStamp"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Класс для добавления штампов (водяного знака или фона) в PDF‑файлы."
type: docs
weight: 320
url: /ru/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

Класс для добавления штампов (водяного знака или фона) в PDF‑файлы.

Тип PdfFileStamp предоставляет следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfFileStamp(input_file, output_file) | Инициализирует новый экземпляр класса PdfFileStamp |
| PdfFileStamp(input_stream, output_stream) | Инициализирует новый экземпляр класса PdfFileStamp |
| PdfFileStamp(input_file, output_file, keep_security) | Инициализирует новый экземпляр класса PdfFileStamp |
| PdfFileStamp(input_stream, output_stream, keep_security) | Инициализирует новый экземпляр класса PdfFileStamp |
| PdfFileStamp() | Конструктор класса PdfFileStamp.<br/>            Входной и выходной файлы могут быть указаны через соответствующие свойства. |
| PdfFileStamp(document) | Инициализирует новый экземпляр класса PdfFileStamp |
| PdfFileStamp(document, output_file) | Инициализирует новый экземпляр класса PdfFileStamp |
| PdfFileStamp(document, output_stream) | Инициализирует новый экземпляр класса PdfFileStamp |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
| optimize_size | Получает или задает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. <br/>            Это позволяет уменьшить размер результирующего файла, но может привести к более медленному выполнению и большим требованиям к памяти.<br/>            Значение по умолчанию: false. |
| keep_security | Сохраняет безопасность, если true. (Эта функция будет реализована в следующих версиях). |
| input_file | Получает или задает имя и путь входного файла. |
| input_stream | Получает или задает входной поток. |
| output_file | Получает или задает имя и путь выходного файла. |
| output_stream | Получает или задает выходной поток. |
| page_number_rotation | Получает или задает поворот номера страницы. Поворот задается в градусах. По умолчанию 0. |
| page_height | Получает высоту первой страницы в исходном файле. |
| page_width | Получает ширину первой страницы во входном файле. |
| starting_number | Получает или задает начальный номер первой страницы во входном файле. Последующие страницы будут нумероваться, начиная с этого значения. <br/>            Например, если StartingNumber установлен в 100, страницы документа будут иметь номера 100, 101, 102... |
| numbering_style | Получает или задает стиль нумерации страниц. Возможные значения: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | ID штампа следующего добавляемого штампа (включая заголовки/колонтитулы страниц/номера страниц). |
| POS_BOTTOM_MIDDLE | Позиция внизу посередине. |
| POS_BOTTOM_RIGHT | Позиция внизу справа. |
| POS_UPPER_RIGHT | Позиция вверху справа. |
| POS_SIDES_RIGHT | Позиция справа. |
| POS_UPPER_MIDDLE | Позиция вверху посередине. |
| POS_BOTTOM_LEFT | Позиция внизу слева. |
| POS_SIDES_LEFT | Позиция слева. |
| POS_UPPER_LEFT | Позиция вверху слева. |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(src_file) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_stream) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_doc) | Привязывает PDF-документ для редактирования. |
| save(dest_file) | Сохраняет результат в указанный файл. |
| save(dest_stream) | Сохраняет документ в указанный поток. |
| add_page_number(format_string) | Добавить номер страницы в файл. Текст номера страницы может содержать знак #, который будет заменён номером страницы. <br/>            Номер страницы размещается внизу страницы, по горизонтали центрирован. |
| add_page_number(formatted_text) | Добавляет номер страницы на страницу. Номер страницы может содержать знак #, который будет заменён номером страницы.<br/>            Номер страницы размещается внизу страницы, по горизонтали центрирован. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | Добавляет номер страницы к страницам документа. |
| add_page_number(format_string, x, y) | Добавляет номер страницы к страницам документа. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | Добавляет номер страницы к страницам документа. |
| add_page_number(formatted_text, x, y) | Добавляет номер страницы к страницам документа. |
| add_page_number(format_string, position) | Добавляет номер страницы к страницам документа. |
| add_page_number(formatted_text, position) | Добавляет номер страницы к страницам документа. |
| add_header(formatted_text, top_margin) | Добавляет заголовок на страницу. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | Добавляет заголовок на страницу. |
| add_header(image_file, top_margin) | Добавляет изображение в качестве заголовка к страницам файла. |
| add_header(image_file, top_margin, left_margin, right_margin) | Добавляет изображение в качестве заголовка к страницам файла. |
| add_header(image_stream, top_margin) | Добавляет изображение в качестве заголовка на страницы. |
| add_header(input_stream, top_margin, left_margin, right_margin) | Добавляет изображение в качестве заголовка на страницы. |
| add_footer(formatted_text, bottom_margin) | Добавляет нижний колонтитул к страницам документа. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | Добавляет нижний колонтитул к страницам документа. |
| add_footer(image_file, bottom_margin) | Добавляет изображение в качестве нижнего колонтитула к страницам документа. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | Добавляет изображение в качестве нижнего колонтитула к страницам документа. |
| add_footer(image_stream, bottom_margin) | Добавляет изображение в качестве нижнего колонтитула страницы. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | Добавляет изображение в качестве нижнего колонтитула страницы. |
| close() | Закрывает открытые файлы и сохраняет изменения. <br/>            Предупреждение. Если указаны входные или выходные потоки, они не закрываются методом Close() method. |
| add_stamp(stamp) | Добавляет штамп в файл. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

