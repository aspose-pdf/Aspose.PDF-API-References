---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter metod. Exporterar data från databas till tabell
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase metod

Exporterar data från databas till tabell.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connectString | Sträng | Anslutningssträng för databas. |
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

### Se Även

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)