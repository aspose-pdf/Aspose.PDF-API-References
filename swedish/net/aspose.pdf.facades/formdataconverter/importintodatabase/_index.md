---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter-metod. Importerar data från tabell till databas
type: docs
weight: 110
url: /sv/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## FormDataConverter.ImportIntoDataBase metod

Importerar data från tabell till databas.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connectString | Sträng | Anslutningssträng för databasen. |
| dbType | DataType | Typ av databasanslutning: OLEDB eller ODBC. |

## Exempel

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

### Se Även

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)