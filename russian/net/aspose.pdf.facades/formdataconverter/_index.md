---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.FormDataConverter. Представляет класс для преобразования данных из одного формата в другой формат. Он может преобразовывать данные из fdf/xml/pdf/xfdf в OLEDB/OdbcDB. Он также может преобразовывать данные из OLEDB/OdbcDB в данные в fdf/xml/xfdf. Он может преобразовывать fdf в xml с "жестко заданным" тегом.
type: docs
weight: 4320
url: /ru/net/aspose.pdf.facades/formdataconverter/
---
## Класс FormDataConverter

Представляет класс для преобразования данных из одного формата в другой формат. Он может преобразовывать данные из fdf/xml/pdf/xfdf в OLEDB/OdbcDB. Он также может преобразовывать данные из OLEDB/OdbcDB в данные в fdf/xml/xfdf. Он может преобразовывать fdf в xml с "жестко заданным" тегом.

```csharp
public sealed class FormDataConverter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData очистит таблицу перед экспортом данных. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable создаст необходимое поле, если оно не существует в таблице. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase создаст таблицу, если она не существует. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase удалит существующую таблицу и создаст новую таблицу, если это свойство установлено в true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Получает или задает средний контейнер данных, одну DataTable. Он должен быть определен перед преобразованием данных из одного формата в другой формат. Столбцы и TableName DataTable должны быть определены. TableName - это имя таблицы в базе данных. Имя столбца каждого столбца - это квалифицированное имя поля pdf. Заголовок каждого столбца - это имя столбца таблицы в базе данных. Если имя поля совпадает с именем столбца таблицы, заголовок не нужно указывать. |

## Методы

| Имя | Описание |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Этот метод устарел. Пожалуйста, используйте ConvertToStreams() вместо этого. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Преобразует файлы потоков в таблицу. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Преобразует данные в таблице в потоки. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Экспортирует данные из базы данных в таблицу. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Импортирует данные из таблицы в базу данных. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Преобразует файл FDF в XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Преобразует файл данных формы XML в формат FDF. |

### См. также

* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)