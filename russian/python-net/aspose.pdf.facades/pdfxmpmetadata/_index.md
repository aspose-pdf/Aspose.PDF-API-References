---
title: "PdfXmpMetadata"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Класс для работы с метаданными XMP."
type: docs
weight: 380
url: /ru/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

Класс для работы с метаданными XMP.

Тип PdfXmpMetadata раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfXmpMetadata() | Конструктор для PdfXmpMetadata. |
| PdfXmpMetadata(document) | Инициализирует новый экземпляр класса PdfXmpMetadata |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
| ключи | Получает ключи из словаря. |
| значения | Получает коллекцию значений в словаре. |
| is_fixed_size | Возвращает true, если коллекция имеет фиксированный размер. |
| is_synchronized | Возвращает true, если коллекция синхронизирована. |
| sync_root | Получает объект синхронизации коллекции. |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(src_file) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_stream) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_doc) | Привязывает PDF-документ для редактирования. |
| save(dest_file) | Сохраняет документ PDF в указанный файл. |
| save(dest_stream) | Сохраняет документ PDF в указанный поток. |
| add(key, value) | Добавляет значение в XMP-метаданные. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | Добавляет поле расширения в метаданные. |
| add(key, value) | Добавляет новый элемент в объект словаря. |
| add(key, value) | Добавляет поле расширения в метаданные. |
| remove(key) | Удаляет элемент с указанным ключом. |
| remove(key) | Удаляет ключ из словаря. |
| contains(key) | Проверяет, содержит ли словарь указанный ключ. |
| contains(property) | Проверяет, содержит ли словарь указанное свойство. |
| get_xmp_metadata() | Получает XmpMetadata входного pdf в формате xml. |
| get_xmp_metadata(name) | Получить часть XmpMetadata входного pdf в соответствии с именем метаданных. |
| close() | Освобождает любые ресурсы, связанные с текущим фасадом. |
| register_namespace_uri(prefix, namespace_uri) | Регистрирует URI пространства имён. |
| get_namespace_uri_by_prefix(prefix) | Получает URI пространства имён по префиксу. |
| get_prefix_by_namespace_uri(namespace_uri) | Получает префикс по URI пространства имён. |
| contains_key(key) | Определяет, содержит ли этот словарь указанный ключ. |
| try_get_value(key, value) | Пытается найти ключ в словаре и получить значение, если найдено. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

