---
title: "FileSpecification"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Класс, представляющий вложенный файл."
type: docs
weight: 360
url: /ru/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

Класс, представляющий вложенный файл.

Тип FileSpecification раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| FileSpecification(file) | Инициализирует новый экземпляр класса FileSpecification |
| FileSpecification(stream, name) | Инициализирует новый экземпляр класса FileSpecification |
| FileSpecification(file, description) | Инициализирует новый экземпляр класса FileSpecification |
| FileSpecification(stream, name, description) | Инициализирует новый экземпляр класса FileSpecification |
| FileSpecification(file_name, annot) | Инициализирует новый экземпляр класса FileSpecification |
| FileSpecification() | Создайте новую пустую спецификацию файла. |
## Свойства
| Имя | Описание |
| :- | :- |
| кодировка | Получает или задает формат кодирования.<br/>            Возможные значения: Zip - файл сжат с помощью ZIP, <br/>            None - файл не сжат. |
| include_contents | Если true, содержимое файла будет включено в спецификацию файла. |
| encrypted_payload | Получает зашифрованные полезные данные. |
| описание | Получает или задает текст, связанный со спецификацией файла. |
| af_relationship | Связанное файловое отношение. |
| stream_contents | Получает содержимое файла в виде потока. <br/>            Содержимое не загружается в память, что позволяет уменьшить использование памяти.<br/>            Однако этот поток не поддерживает позиционирование и свойство Length. Если вам нужны эти функции, пожалуйста, используйте свойство Contents вместо этого. |
| содержимое | Получает или задает содержимое файла. <br/>            Это свойство возвращает данные, загруженные в память, что может вызвать исключение Out of memory при больших объёмах данных.<br/>            Чтобы уменьшить использование памяти, пожалуйста, используйте StreamContents. |
| params | Получает параметры файла. |
| mime_type | Получает подтип встроенного файла |
| name | Получает или задает имя спецификации файла. |
| unicode_name | Получает или задает Unicode-имя спецификации файла. |
| file_system | Получает или задает имя файловой системы. |
## Методы
| Имя | Описание |
| :- | :- |
| get_value(key) | Получает параметр, специфичный для приложения. |
| set_value(key, value) | Задает параметр, специфичный для приложения. |

### См. также

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

