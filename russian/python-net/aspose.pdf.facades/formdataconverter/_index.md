---
title: "FormDataConverter"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет класс для преобразования данных из одного формата в другой.<br/>            Может преобразовывать данные в fdf/xml/pdf/xfdf в OLEDB/OdbcDB.<br/>            Также может преобразовывать данные в OLEDB/OdbcDB в данные в fdf/xml/xfdf.<br/>            Может преобразовать fdf в xml с тегом \"hard-named\"."
type: docs
weight: 100
url: /ru/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

Представляет класс для преобразования данных из одного формата в другой.<br/>            Может преобразовывать данные в fdf/xml/pdf/xfdf в OLEDB/OdbcDB.<br/>            Также может преобразовывать данные в OLEDB/OdbcDB в данные в fdf/xml/xfdf.<br/>            Может преобразовать fdf в xml с тегом "hard-named".

Тип FormDataConverter раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| FormDataConverter() | Инициализирует новый экземпляр класса FormDataConverter |
## Свойства
| Имя | Описание |
| :- | :- |
| create_missing_field | ConvertToDataTable создаст требуемое поле, если оно не существует в таблице. |
| replace_existing_table | ImportIntoDatabase удалит существующую таблицу и создаст новую, если это свойство установлено в true. |
| clear_table_before_export | ExportFromData очистит таблицу перед экспортом данных. |
| create_missing_table | ImportIntoDatabase создаст таблицу, если она не существует. |
## Методы
| Имя | Описание |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | Преобразовать файл данных формы XML импорта/экспорта в формат FDF. |
| convert_fdf_to_xml(source_fdf, dest_xml) | Преобразовать файл FDF в XML. |
| convert_to_data_table(source_streams, source_type) | Преобразовать файлы потоков в таблицу. |
| import_into_data_base(connect_string, db_type) | Импортирует данные из таблицы в базу данных. |
| export_from_data_base(connect_string, db_type) | Экспортирует данные из базы данных в таблицу. |
| convert_to_streams(dest_stream, dest_type) | Преобразовать данные в таблице в потоки. |
| conver_to_streams(dest_stream, dest_type) | Этот метод устарел. Пожалуйста, используйте ConvertToStreams() вместо него. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

