---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter 方法。将数据从表导入数据库
type: docs
weight: 110
url: /zh/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## FormDataConverter.ImportIntoDataBase 方法

将数据从表导入数据库。

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| connectString | 字符串 | 数据库的连接字符串。 |
| dbType | 数据类型 | 数据库连接的类型：OLEDB 或 ODBC。 |

## 示例

```csharp
FormDataConverter fc = new FormDataConverter();
DataTable table = new DataTable();
table.TableName = "test";
table.Columns.Add("TEXT_VALUE");
table.Columns.Add("INT_VALUE");
fc.Table = table;
DataRow row = table.NewRow();
row["TEXT_VALUE"] = "AAA";
row["INT_VALUE"] = "123";
table.Rows.Add(row);
string connection = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=ConverterDatabase.mdb";
fc.ImportIntoDataBase(connection, DataType.OLEDB);
```

### 另请参见

* 枚举 [DataType](../../datatype/)
* 类 [FormDataConverter](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)