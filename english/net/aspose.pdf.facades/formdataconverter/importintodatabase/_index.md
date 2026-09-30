---
title: "FormDataConverter.ImportIntoDataBase"
linktitle: "ImportIntoDataBase"
articleTitle: "ImportIntoDataBase"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormDataConverter method. Imports data from table into database."
type: docs
weight: 50
url: "/net/aspose.pdf.facades/formdataconverter/importintodatabase/"
product_version: "26.9.0"
---
## FormDataConverter.ImportIntoDataBase method

Imports data from table into database.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connectString | String | Connection string of database. |
| dbType | DataType | Type of database connection: OLEDB or ODBC. |

## Examples

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

### See Also

* enum [DataType](../../../aspose.pdf.lowcode/datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

