---
title: "PdfFileInfo"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет класс для доступа к метаинформации PDF‑документа."
type: docs
weight: 270
url: /ru/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

Представляет класс для доступа к метаинформации PDF‑документа.

Тип PdfFileInfo раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfFileInfo() | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo со значениями по умолчанию. |
| PdfFileInfo(input_stream) | Инициализирует новый экземпляр класса PdfFileInfo |
| PdfFileInfo(input_stream, password) | Инициализирует новый экземпляр класса PdfFileInfo |
| PdfFileInfo(input_file) | Инициализирует новый экземпляр класса PdfFileInfo |
| PdfFileInfo(input_file, password) | Инициализирует новый экземпляр класса PdfFileInfo |
| PdfFileInfo(document) | Инициализирует новый экземпляр класса PdfFileInfo |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
| author | Получает или задает информацию об авторе PDF‑документа. |
| is_encrypted | Проверяет, зашифрован ли PDF‑документ. |
| is_pdf_file | Проверяет, является ли исходный ввод действительным PDF‑файлом. |
| use_strict_validation | Использует строгие правила проверки через свойство [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/). |
| creation_date | Получает или задает информацию о дате создания PDF‑документа. |
| creator | Получает или задает информацию о создателе PDF‑документа. |
| has_collection | Возвращает true, если текущий входной файл является файлом 'Portfolio', содержащим коллекцию PDF‑файлов. |
| input_file | Получает или задает входной файл. |
| input_stream | Получает или задает входной поток. |
| keywords | Получает или задает информацию о ключевых словах PDF‑документа. |
| mod_date | Получает или задает информацию о дате ModDate PDF‑документа. |
| number_of_pages | Получает количество страниц документа. |
| producer | Получает информацию о производителе PDF‑документа. |
| subject | Получает или задает информацию о предмете PDF‑документа. |
| title | Получает или задает информацию о заголовке PDF‑документа. |
| password_type | Возвращает тип пароля, который был передан при создании экземпляра PdfFileInfo. См. возможные значения в [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Обратите внимание, что PDF‑документ может быть открыт как с пользовательским (или открывающим) паролем, так и с паролем владельца (или паролем разрешений, редактирования). |
| has_open_password | Возвращает true, если для открытия защищённого паролем PDF‑документа требуется пароль. |
| has_edit_password | Возвращает true, если для изменения разрешений или свойства безопасности документа требуется пароль.<br/>            Обратите внимание, что это свойство можно прочитать только если в конструкторе [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) был предоставлен действительный пароль.<br/>            В случае, когда PasswordType имеет значение Inaccessible (это означает, что был предоставлен недействительный пароль), чтение этого свойства завершится ошибкой [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/). |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(src_doc) | Инициализирует фасад. |
| bind_pdf(src_file) | Инициализирует фасад. |
| bind_pdf(src_stream) | Инициализирует фасад. |
| save(dest_stream) | Сохранить обновлённый PDF‑документ в указанный поток. |
| save(dest_file) | Сохранить обновлённый PDF‑документ в указанный файл. |
| save_new_info(output_stream) | Сохранить обновлённый PDF‑документ в указанный поток. |
| save_new_info(output_file) | Сохранить обновлённый PDF‑документ в указанный файл. |
| close() | Деинициализирует экземпляр. |
| clear_info() | Очищает всю метаинформацию PDF‑документа. |
| get_document_privilege() | Получает настройки привилегий PDF‑документа. |
| get_meta_info(name) | Получает пользовательскую информацию PDF‑документа по имени свойства. Если нет свойства, соответствующего имени, будет возвращена пустая строка. |
| get_page_height(page_num) | Получает высоту указанной страницы. |
| get_page_rotation(page_num) | Получает вращение указанной страницы. |
| get_page_width(page_num) | Получает ширину указанной страницы. |
| get_page_x_offset(page_num) | Получает горизонтальное смещение области отображения указанной страницы. |
| get_page_y_offset(page_num) | Получает вертикальное смещение области отображения указанной страницы. |
| get_pdf_version() | Получает информацию о версии PDF‑документа. |
| set_meta_info(name, value) | Устанавливает пользовательскую информацию PDF‑документа. |
| save_new_info_with_xmp(output_file_name) | Изменяет явно указанные свойства, устанавливая информацию о файле; остальные свойства остаются без изменений. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

