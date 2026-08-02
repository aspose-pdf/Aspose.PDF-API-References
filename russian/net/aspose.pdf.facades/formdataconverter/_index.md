---
title: "Класс FormDataConverter"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.FormDataConverter. Представляет класс для преобразования данных из одного формата в другой. Он может конвертировать данные в fdf/xml/pdf/xfdf в OLEDB/OdbcDB. Он также может конвертировать данные из OLEDB/OdbcDB в данные в fdf/xml/xfdf. Он может преобразовать fdf в xml с жёстко заданным тегом."
type: docs
weight: 4440
url: /ru/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

Представляет класс для преобразования данных из одного формата в другой. Он может конвертировать данные в fdf/xml/pdf/xfdf в OLEDB/OdbcDB. Он также может конвертировать данные в OLEDB/OdbcDB в данные в fdf/xml/xfdf. Он может преобразовать fdf в xml с тегом "hard-named".

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
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable создаст требуемое поле, если оно не существует в таблице. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase создаст таблицу, если она не существует. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase удалит существующую таблицу и создаст новую, если это свойство установлено в true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Получает или задает промежуточный контейнер данных, один DataTable. Он должен быть определён перед преобразованием данных из одного формата в другой. Должны быть определены Columns и TableName DataTable. TableName — это имя таблицы в базе данных. ColumnName каждой колонки является квалифицированным именем поля pdf. Caption каждой колонки — это имя столбца таблицы в базе данных. Если имя поля совпадает с именем столбца таблицы, указывать Caption не требуется. |

## Методы

| Имя | Описание |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Этот метод устарел. Пожалуйста, используйте ConvertToStreams() вместо него. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Преобразовать файлы потоков в таблицу. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Преобразовать данные в таблице в потоки. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Экспортирует данные из базы данных в таблицу. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Импортирует данные из таблицы в базу данных. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Преобразовать файл FDF в XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Преобразовать файл данных формы XML импорт/экспорт в формат FDF. |

### См. также

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


