---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter 方法。将数据从数据库导出到表中
type: docs
weight: 100
url: /zh/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase 方法

将数据从数据库导出到表中。

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| connectString | 字符串 | 数据库的连接字符串。 |
| dbType | 数据类型 | 连接类型：OLEDB 或 ODBC。 |

## 示例

```csharp
FormDataConverter fc = new FormDataConverter();
string connection = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=ConverterDatabase.mdb";
DataTable table = new DataTable();
table.TableName = "TestSource";
table.Columns.Add("TEXT_VALUE");
table.Columns.Add("INT_VALUE");
fc.Table = table;
fc.ExportFromDataBase(connection, DataType.OLEDB);
```

### 另请参阅

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)