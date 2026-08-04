---
title: "FormDataConverter"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示一个将数据从一种格式转换为另一种格式的类。<br/>            它可以将 fdf/xml/pdf/xfdf 中的数据转换为 OLEDB/OdbcDB。<br/>            它也可以将 OLEDB/OdbcDB 中的数据转换为 fdf/xml/xfdf。<br/>            它可以将 fdf 转换为带有 \"hard-named\" 标记的 xml。"
type: docs
weight: 100
url: /zh/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

表示一个将数据从一种格式转换为另一种格式的类。<br/>            它可以将 fdf/xml/pdf/xfdf 中的数据转换为 OLEDB/OdbcDB。<br/>            它也可以将 OLEDB/OdbcDB 中的数据转换为 fdf/xml/xfdf。<br/>            它可以将 fdf 转换为带有 "hard-named" 标记的 xml。

FormDataConverter 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| FormDataConverter() | 初始化 FormDataConverter 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| create_missing_field | 如果表中不存在，ConvertToDataTable 将创建必需的字段。 |
| replace_existing_table | 如果将此属性设置为 true，ImportIntoDatabase 将删除现有表并创建新表。 |
| clear_table_before_export | ExportFromData 将在数据导出前清空表。 |
| create_missing_table | 如果表不存在，ImportIntoDatabase 将创建表。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | 将 XML 导入/导出表单数据文件转换为 FDF 格式。 |
| convert_fdf_to_xml(source_fdf, dest_xml) | 将 FDF 文件转换为 XML。 |
| convert_to_data_table(source_streams, source_type) | 将流文件转换为表。 |
| import_into_data_base(connect_string, db_type) | 将数据从表导入到数据库。 |
| export_from_data_base(connect_string, db_type) | 将数据从数据库导出到表。 |
| convert_to_streams(dest_stream, dest_type) | 将表中的数据转换为流。 |
| conver_to_streams(dest_stream, dest_type) | 此方法已过时。请改用 ConvertToStreams()。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

