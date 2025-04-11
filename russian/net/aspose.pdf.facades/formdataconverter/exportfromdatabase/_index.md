---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: Метод FormDataConverter. Экспортирует данные из базы данных в таблицу
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## Метод FormDataConverter.ExportFromDataBase

Экспортирует данные из базы данных в таблицу.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connectString | String | Строка подключения к базе данных. |
| dbType | DataType | Тип подключения: OLEDB или ODBC. |

## Примеры

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

### См. также

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)