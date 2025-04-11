---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: Метод FormDataConverter. Импортирует данные из таблицы в базу данных
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## Метод FormDataConverter.ImportIntoDataBase

Импортирует данные из таблицы в базу данных.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connectString | String | Строка подключения к базе данных. |
| dbType | DataType | Тип подключения к базе данных: OLEDB или ODBC. |

## Примеры

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

### См. также

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)