---
title: "PdfFormatConversionOptions"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "представляет набор параметров для преобразования PDF‑документа"
type: docs
weight: 1220
url: /ru/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

представляет набор параметров для преобразования PDF‑документа

Тип PdfFormatConversionOptions раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | Инициализирует новый экземпляр класса PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format) | Инициализирует новый экземпляр класса PdfFormatConversionOptions |
| PdfFormatConversionOptions(format) | Инициализирует новый экземпляр класса PdfFormatConversionOptions |
| PdfFormatConversionOptions(format, action) | Инициализирует новый экземпляр класса PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | Инициализирует новый экземпляр класса PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_stream, format, action) | Инициализирует новый экземпляр класса PdfFormatConversionOptions |
## Свойства
| Имя | Описание |
| :- | :- |
| is_async_image_streams_conversion_mode | Получает/устанавливает выполнение потоков изображений в асинхронном режиме. |
| is_low_memory_mode | Включён ли режим конвертации с низким потреблением памяти |
| формат | Формат PDF. |
| log_file_name | Путь к файлу, в котором будут сохраняться комментарии. |
| log_stream | Поток, в котором будут сохраняться комментарии. |
| error_action | Действие для объектов, которые нельзя конвертировать |
| transparency_action | Действие для объектов с маской изображения |
| convert_soft_mask_action | Действие для изображений с мягкой маской. |
| по умолчанию | Получает объект PdfFormatConversionOptions с параметрами по умолчанию |
| non_specification_cases | Содержит флаги для управления процессом конвертации PDF/A в случаях, когда исходный документ<br/>            не соответствует спецификации PDF/A. |
| symbolic_font_encoding_strategy | Стратегия копирования данных кодировки для символических шрифтов, если символический TrueType‑шрифт<br/>            имеет более одной подтаблицы кодировки. |
| align_text | Этот флаг управляет выравниванием текста в конвертированном документе. По умолчанию конвертация документа <br/>            не влияет на выравнивание текста и оставляет его без изменений. Однако в некоторых случаях замена шрифтов<br/>            приводит к наложению текста или появлению лишних пробелов в конвертированном документе. Когда этот флаг установлен,<br/>            выполняются специальные операции выравнивания. Этот флаг следует устанавливать только для документов,<br/>            в которых есть проблемы с наложенным текстом или лишними пробелами, так как использование этого флага снижает<br/>            производительность и в некоторых случаях может повредить содержимое текста. |
| pua_text_processing_strategy | Стратегия обработки символов из Unicode Private Use Area (PUA). |
| optimize_file_size | Получает или задает флаг, который включает/выключает специальный режим конвертации для получения PDF/A документа с уменьшенным размером файла.<br/>            Сейчас этот флаг влияет на оптимизацию шрифтов, используемых в PDF‑документе, возможно, в будущем этот флаг <br/>            также будет использоваться для включения оптимизации других структур данных, таких как графика.  <br/>            Установка этого флага и режима может значительно уменьшить размер файла, но одновременно может<br/>            значительно снизить производительность конвертации. |
| exclude_fonts_strategy | Стратегия(ии) исключения избыточных шрифтов и уменьшения размера файла документа. <br/>            Этот параметр имеет смысл только когда флаг [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) установлен в true.<br/>            По умолчанию используется комбинация стратегий [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) и<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/). |
| font_embedding_options | Опции для случаев, когда невозможно встроить некоторые шрифты в PDF‑документ. |
| unicode_processing_rules | Правила решения проблем с отображением Unicode. Может быть null. |
| icc_profile_file_name | Получает или задает имя файла ICC‑профиля. Если значение null, используется профиль ICC по умолчанию. |
| not_accessible_fonts | Это свойство является внешним свойством. Оно содержит все шрифты (имена шрифтов), которые не были найдены на компьютере <br/>            при последней конвертации PDF/A. |
| is_transfer_info | Получает или задает, следует ли передавать данные из Info в Metadata при конвертации в PDF 2.0. По умолчанию true. |
| align_strategy | Стратегия выравнивания текста. Этот параметр имеет смысл только когда флаг [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) установлен в true. |

### См. также

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

