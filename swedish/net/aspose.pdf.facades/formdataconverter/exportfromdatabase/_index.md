---
title: "FormDataConverter.ExportFromDataBase"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormDataConverter-metoden. Exporterar data från databasen till tabellen"
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase method

Exporterar data från databasen till en tabell.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connectString | String | Anslutningssträng för databasen. |
| dbType | DataType | Anslutningstyp: OLEDB eller ODBC. |

## Exempel

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

### Se även

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


