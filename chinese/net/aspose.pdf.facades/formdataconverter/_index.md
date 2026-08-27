---
title: "类 FormDataConverter"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.FormDataConverter 类。表示用于在不同格式之间转换数据的类。它可以将 fdf/xml/pdf/xfdf 中的数据转换为 OLEDB/OdbcDB，也可以将 OLEDB/OdbcDB 中的数据转换为 fdf/xml/xfdf。它还能将 fdf 转换为带有硬编码标签的 xml。"
type: docs
weight: 4440
url: /zh/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

表示一个将数据从一种格式转换为另一种格式的类。它可以将 fdf/xml/pdf/xfdf 中的数据转换为 OLEDB/OdbcDB。它也可以将 OLEDB/OdbcDB 中的数据转换为 fdf/xml/xfdf。它可以将 fdf 转换为带有 "hard-named" 标记的 xml。

```csharp
public sealed class FormDataConverter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData 在导出数据前会清空表。 |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable 如果表中不存在所需字段，将创建该字段。 |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase 如果表不存在，将创建表。 |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | 如果将此属性设为 true，ImportIntoDatabase 将删除现有表并创建新表。 |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | 获取或设置中间数据容器，即一个 DataTable。必须在将数据从一种格式转换为另一种格式之前定义它。应定义该 DataTable 的 Columns 和 TableName。TableName 是数据库中表的名称。每列的 ColumnName 是 pdf 的合格字段名。每列的 Caption 是数据库中表的列名。如果字段名与表列名相同，则无需指定 Caption。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | 此方法已过时。请改用 ConvertToStreams()。 |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | 将流文件转换为表。 |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | 将表中的数据转换为流。 |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | 将数据库中的数据导出到表中。 |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | 将表格中的数据导入数据库。 |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | 将 FDF 文件转换为 XML。 |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | 将 XML 导入/导出表单数据文件转换为 FDF 格式。 |

### 另请参见

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


