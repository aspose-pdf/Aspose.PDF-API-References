---
title: "PdfFileEditor"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Реализует операции с объединением PDF‑файлов, разбиением, извлечением страниц, созданием буклета и т.д."
type: docs
weight: 220
url: /ru/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

Реализует операции с PDF‑файлом: конкатенацию, разбиение, извлечение страниц, создание буклета и т.д.

Тип PdfFileEditor раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfFileEditor() | Инициализирует новый экземпляр класса PdfFileEditor |
## Свойства
| Имя | Описание |
| :- | :- |
| conversion_log | Получает журнал процесса конвертации. |
| merge_duplicate_layers | Необязательное содержимое объединённых документов с одинаковыми именами будет объединено в один слой в результирующем документе, если это свойство истинно. <br/>            Иначе слои с одинаковыми именами будут сохранены как отдельные слои в результирующем документе. |
| copy_outlines | Если true, то контуры будут скопированы. |
| copy_logical_structure | Если true, то логическая структура файла копируется при выполнении объединения. |
| merge_duplicate_outlines | Если true, дублирующие контуры объединяются. |
| preserve_user_rights | Если true, права пользователя первого документа применяются к объединённому документу. Права пользователя всех остальных документов игнорируются. |
| incremental_updates | Если true, при объединении выполняются инкрементные обновления. |
| optimize_size | Получает или задает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. <br/>            Это позволяет уменьшить размер результирующего файла, но может привести к более медленному выполнению и большим требованиям к памяти.<br/>            Значение по умолчанию: false. |
| corrupted_items | Массив обнаруженных проблем, возникших при выполнении объединения. Для каждого повреждённого документа, переданного в Concatenate() <br/>            создаётся новая запись CorruptedItem.<br/>            Это свойство может использоваться только когда CorruptedFileAction имеет значение ConcatenateIgnoringCorrupted. |
| corrupted_file_action | Это свойство определяет поведение, когда процесс объединения встречает повреждённый файл.<br/>            Возможные значения: StopWithError и ConcatenateIgnoringCorrupted. |
| owner_password | Устанавливает пароль владельца, если исходный входной PDF‑файл зашифрован.<br/>            Это свойство пока не реализовано. |
| allow_concatenate_exceptions | Если установлено в true, исключения выбрасываются при возникновении ошибки. Иначе исключения не выбрасываются, и методы возвращают false при неудаче. |
| close_concatenated_streams | Если установлено в true, потоки закрываются после операции. |
| unique_suffix | Формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при конкатенации форм.<br/>            Эта строка должна содержать подстроку %NUM%, которая будет заменена числами.<br/>            Например, если UniqueSuffix = \"ABC%NUM%\", то для поля \"fieldName\" имена будут:<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 и т.д. |
| keep_actions | Если true, действия будут скопированы из исходных документов. Значение по умолчанию: true. |
| keep_fields_unique | Если true, имена полей будут сделаны уникальными при конкатенации форм.<br/>            К именам полей будут добавлены суффиксы, шаблон суффикса можно указать в свойстве UniqueSuffix. |
| remove_signatures | Если true, все подписи будут удалены из полей (поля останутся); иначе могут возникнуть недействительные подписи. |
| use_disk_buffer | Если эта опция используется, конечный документ будет периодически сохраняться на диск, а дальнейшая конкатенация будет применяться к нему как инкрементные обновления. |
| concatenation_packet_size | Количество документов, конкатенированных до создания нового инкрементного обновления во время конкатенации, когда UseDiskBuffer установлен в true. |
## Методы
| Имя | Описание |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | Конкатенирует два файла. |
| try_concatenate(src, dest) | Конкатенирует документы. |
| try_concatenate(input_files, output_file) | Конкатенирует файлы в один файл. |
| try_concatenate(input_stream, output_stream) | Конкатенирует файлы |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Конкатенирует два файла. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Конкатенирует файлы |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | Добавляет страницы, выбранные из массива документов в portStreams.<br/>            Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage. |
| try_append(input_file, port_files, start_page, end_page, output_file) | Добавляет страницы, выбранные из документов portFiles. <br/>            Результирующий документ включает firstInputFile и все страницы документов portFiles в диапазоне от startPage до endPage. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | Вставляет страницы из другого файла во входной PDF-файл. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | Вставляет страницы из другого файла во входной PDF-файл. |
| try_delete(input_file, page_number, output_file) | Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый PDF-файл. |
| try_delete(input_stream, page_number, output_stream) | Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый PDF-файл. |
| try_extract(input_file, start_page, end_page, output_file) | Извлекает страницы из входного файла, сохраняет как новый PDF-файл. |
| try_extract(input_file, page_number, output_file) | Извлекает страницы, указанные массивом номеров, сохраняет как новый PDF-файл. |
| try_extract(input_stream, page_number, output_stream) | Извлекает страницы, указанные массивом номеров, сохраняет как новый PDF-файл. |
| try_split_from_first(input_file, location, output_file) | Разделяет PDF-файл с первой страницы до указанного места и сохраняет переднюю часть как новый файл. |
| try_split_from_first(input_stream, location, output_stream) | Разделяет с начала до указанного места и сохраняет переднюю часть в выходном потоке. |
| try_split_to_end(input_file, location, output_file) | Разделяет от указанного места и сохраняет заднюю часть как новый файл. |
| try_split_to_end(input_stream, location, output_stream) | Разделяет с указанного места и сохраняет заднюю часть как новый поток Stream. |
| try_make_booklet(input_file, output_file) | Создаёт брошюру из входного файла в выходной файл. |
| try_make_booklet(input_stream, output_stream) | Создаёт брошюру из InputStream в outputStream. |
| try_make_booklet(input_file, output_file, page_size) | Создаёт брошюру из inputFile в outputFile. |
| try_make_booklet(input_stream, output_stream, page_size) | Создаёт брошюру из входного потока и сохраняет результат в выходной поток. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | Создаёт настроенную брошюру из firstInputFile в outputFile. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | Создаёт настроенную брошюру из firstInputStream в outputStream. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Создаёт настроенную брошюру из firstInputFile в outputFile. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Создаёт брошюру из firstInputStream в outputStream. |
| try_make_n_up(input_file, output_file, x, y) | Создаёт документ N-Up из firstInputFile в outputFile. |
| try_make_n_up(input_stream, output_stream, x, y) | Создаёт документ N-Up из входного потока и сохраняет результат в выходной поток. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | Создаёт документ N-Up из первого входного потока в выходной поток. |
| try_make_n_up(first_input_file, second_input_file, output_file) | Создаёт документ N-Up из firstInputFile в outputFile. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | Создаёт документ N-Up из входного потока и сохраняет результат в выходной поток. |
| try_make_n_up(input_files, output_file, is_sidewise) | Создает N‑Up документ из нескольких входных PDF‑файлов в outputFile. <br/>            Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией страниц <br/>            во входных файлах с одинаковым номером страницы. Несколько страниц укладываются горизонтально <br/>            если isSidewise равно true, и вертикально, если isSidewise равно false. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | Создает N‑Up документ из нескольких входных PDF‑потоков в outputStream.<br/>            Каждая страница outputStream будет содержать несколько страниц, которые являются комбинацией страниц <br/>            во входных потоках с одинаковым номером страницы. Несколько страниц укладываются горизонтально <br/>            если isSidewise равно true, и вертикально, если isSidewise равно false. |
| try_make_n_up(input_file, output_file, x, y, page_size) | Создает N‑Up документ из входного файла в outputFile. |
| try_resize_contents(source, destination, pages, parameters) | Изменяет размер содержимого страниц документа. |
| try_resize_contents(source, destination, pages, new_width, new_height) | Изменяет размер содержимого страниц документа. <br/>            Уменьшает содержимое страницы и добавляет поля.<br/>            Новый размер содержимого указывается в единицах пространства по умолчанию. |
| try_resize_contents(source, destination, pages, parameters) | Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля. |
| concatenate(first_input_file, sec_input_file, output_file) | Объединяет файлы и сохраняет результат в объект HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | Объединяет файлы и сохраняет результат в объект HttpResponse. |
| concatenate(src, dest) | Конкатенирует документы. |
| concatenate(input_files, output_file) | Объединяет файлы и сохраняет результат в объект HttpResposnse. |
| concatenate(input_stream, output_stream) | Объединяет файлы и сохраняет результат в объект HttpResponse. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Объединяет файлы и сохраняет результат в объект HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Объединяет файлы и сохраняет результат в объект HttpResponse. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | Добавляет документы к исходному документу и сохраняет результат в объект response. |
| append(input_file, port_files, start_page, end_page, output_file) | Добавляет документы к исходному документу и сохраняет результат в объект HttpResponse. |
| append(input_file, port_file, start_page, end_page, output_file) | Добавляет документы к исходному документу и сохраняет результат в объект HttpResponse. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | Добавляет документы к исходному документу и сохраняет результат в объект response. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | Вставляет содержимое файла в исходный файл и сохраняет результат в объект HttpResponse. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | Вставляет документ в другой документ и сохраняет результат в объект response. |
| insert(input_file, insert_location, port_file, page_number, output_file) | Вставляет содержимое файла в исходный файл и сохраняет результат в объект HttpResponse. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | Вставляет документ в другой документ и сохраняет результат в объект response. |
| delete(input_file, page_number, output_file) | Удаляет указанные страницы из документа и сохраняет результат в объект HttpResponse. |
| delete(input_stream, page_number, output_stream) | Удаляет указанные страницы из документа и сохраняет результат в объект HttpResponse. |
| extract(input_file, start_page, end_page, output_file) | Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse. |
| extract(input_file, page_number, output_file) | Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse. |
| extract(input_stream, start_page, end_page, output_stream) | Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse. |
| extract(input_stream, page_number, output_stream) | Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse. |
| split_from_first(input_file, location, output_file) | Разделяет документ с первой страницы до указанного места и сохраняет результат в объекты HttpResponse. |
| split_from_first(input_stream, location, output_stream) | Разделяет документ от начала до указанного места и сохраняет результат в объект HttpResponse. |
| split_to_end(input_file, location, output_file) | Разделяет с указанного места и сохраняет заднюю часть в объект HttpResponse. |
| split_to_end(input_stream, location, output_stream) | Разделяет с указанного места и сохраняет заднюю часть в объект HttpResponse. |
| make_booklet(input_file, output_file) | Создаёт брошюру из исходного файла и сохраняет результат в объекты HttpResponse. |
| make_booklet(input_stream, output_stream) | Создайте брошюру из PDF‑файла и сохраните её в HttpResponse. |
| make_booklet(input_file, output_file, page_size) | Создаёт брошюру из исходного файла и сохраняет результат в объекты HttpResponse. |
| make_booklet(input_stream, output_stream, page_size) | Создайте брошюру из PDF‑файла и сохраните её в HttpResponse. |
| make_booklet(input_file, output_file, left_pages, right_pages) | Создаёт брошюру из исходного файла и сохраняет результат в объекты HttpResponse. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | Создайте брошюру из PDF‑файла и сохраните её в HttpResponse. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Создаёт брошюру из исходного файла и сохраняет результат в объекты HttpResponse. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Создайте брошюру из PDF‑файла и сохраните её в HttpResponse. |
| make_n_up(input_file, output_file, x, y) | Создаёт документ N‑up и сохраняет результат в объект HttpResponse. |
| make_n_up(input_stream, output_stream, x, y) | Создаёт документ N‑up и сохраняет результат в объект HttpResponse. |
| make_n_up(input_stream, output_stream, x, y, page_size) | Создаёт документ N‑up и сохраняет результат в объект HttpResponse. |
| make_n_up(first_input_file, second_input_file, output_file) | Создаёт документ N‑up и сохраняет результат в объект HttpResponse. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | Создаёт документ N‑up и сохраняет результат в объект HttpResponse. |
| make_n_up(input_files, output_file, is_sidewise) | Создает N‑Up документ из нескольких входных PDF‑файлов в outputFile. <br/>            Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией страниц <br/>            во входных файлах с одинаковым номером страницы. Несколько страниц укладываются горизонтально <br/>            если isSidewise равно true, и вертикально, если isSidewise равно false. |
| make_n_up(input_streams, output_stream, is_sidewise) | Создает N‑Up документ из нескольких входных PDF‑потоков в outputStream.<br/>            Каждая страница outputStream будет содержать несколько страниц, которые являются комбинацией страниц <br/>            во входных потоках с одинаковым номером страницы. Несколько страниц укладываются горизонтально <br/>            если isSidewise равно true, и вертикально, если isSidewise равно false. |
| make_n_up(input_file, output_file, x, y, page_size) | Создаёт документ N‑up и сохраняет результат в объект HttpResponse. |
| split_to_pages(input_file, file_name_template) | Разбивает PDF‑файл на одностраничные документы. |
| split_to_pages(input_stream, file_name_template) | Разбивает PDF‑файл на одностраничные документы и сохраняет его в указанный путь. Путь задаётся шаблоном имени поля. |
| resize_contents(source, destination, pages, parameters) | Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля. Результат сохраняется в объект HttpResponse. |
| resize_contents(source, destination, pages, new_width, new_height) | Изменяет размер содержимого страниц документа. <br/>            Уменьшает содержимое страницы и добавляет поля.<br/>            Новый размер содержимого указывается в единицах пространства по умолчанию. |
| resize_contents(source, destination, pages, new_width, new_height) | Изменяет размер содержимого страниц документа. <br/>            Уменьшает содержимое страницы и добавляет поля.<br/>            Новый размер содержимого указывается в единицах пространства по умолчанию. |
| resize_contents(source, destination, pages, parameters) | Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля. Результат сохраняется в объект HttpResponse. |
| resize_contents(source, pages, parameters) | Изменяет размер страниц документа. Пустые поля добавляются вокруг уменьшенной страницы. |
| resize_contents(source, parameters) | Изменяет размер страниц документа. Пустые поля добавляются вокруг уменьшенной страницы. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Изменяет размер содержимого страниц документа.<br/>            Уменьшает содержимое страницы и добавляет поля.<br/>            Новый размер содержимого указывается в процентах. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Изменяет размер содержимого страниц документа.<br/>            Уменьшает содержимое страницы и добавляет поля.<br/>            Новый размер содержимого указывается в процентах. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Изменяет размер содержимого страницы и добавляет указанные поля. <br/>            Поля указываются в единицах пространства по умолчанию. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Изменяет размер содержимого страницы и добавляет указанные поля. <br/>            Поля указываются в единицах пространства по умолчанию. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Изменяет размер содержимого страницы и добавляет указанные поля.<br/>            Поля указываются в процентах от исходного размера страницы. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Изменяет размер содержимого страницы и добавляет указанные поля.<br/>            Поля указываются в процентах от исходного размера страницы. |
| add_page_break(src, dest, page_breaks) | Добавляет разрывы страниц в страницы документа. |
| add_page_break(src, dest, page_breaks) | Добавляет разрывы страниц в страницы документа. |
| add_page_break(src, dest, page_breaks) | Добавляет разрывы страниц в страницы документа. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

