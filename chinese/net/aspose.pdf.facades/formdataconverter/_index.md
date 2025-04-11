---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormDataConverter 类。表示一个将数据从一种格式转换为另一种格式的类。它可以将 fdf/xml/pdf/xfdf 中的数据转换为 OLEDB/OdbcDB。它还可以将 OLEDB/OdbcDB 中的数据转换为 fdf/xml/xfdf 中的数据。它可以将 fdf 转换为带有“硬命名”标签的 xml。
type: docs
weight: 4320
url: /zh/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

表示一个将数据从一种格式转换为另一种格式的类。它可以将 fdf/xml/pdf/xfdf 中的数据转换为 OLEDB/OdbcDB。它还可以将 OLEDB/OdbcDB 中的数据转换为 fdf/xml/xfdf 中的数据。它可以将 fdf 转换为带有“硬命名”标签的 xml。

```csharp
public sealed class FormDataConverter
```

## Constructors

| Name | Description |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData 将在数据导出之前清除表。 |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable 将在表中不存在时创建所需字段。 |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase 将在表不存在时创建表。 |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase 将删除现有表并创建新表，如果此属性设置为 true。 |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | 获取或设置中间数据容器，一个 DataTable。在将数据从一种格式转换为另一种格式之前必须定义。DataTable 的列和表名应被定义。TableName 是数据库中表的名称。每列的 ColumnName 是 pdf 的合格字段名称。每列的 Caption 是数据库中表的列名。如果字段名称与表列名相同，则不需要指定 Caption。 |

## Methods

| Name | Description |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | 此方法已过时。请改用 ConvertToStreams()。 |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | 将流文件转换为表。 |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | 将表中的数据转换为流。 |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | 从数据库导出数据到表。 |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | 从表导入数据到数据库。 |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | 将 FDF 文件转换为 XML。 |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | 将 XML 导入/导出表单数据文件转换为 FDF 格式。 |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)