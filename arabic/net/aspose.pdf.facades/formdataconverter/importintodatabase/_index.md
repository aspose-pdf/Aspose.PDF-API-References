---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormDataConverter. تستورد البيانات من الجدول إلى قاعدة البيانات
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## طريقة FormDataConverter.ImportIntoDataBase

تستورد البيانات من الجدول إلى قاعدة البيانات.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| connectString | String | سلسلة الاتصال بقاعدة البيانات. |
| dbType | DataType | نوع اتصال قاعدة البيانات: OLEDB أو ODBC. |

## أمثلة

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

### انظر أيضًا

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)