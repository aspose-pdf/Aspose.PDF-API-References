---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter-Methode. Importiert Daten aus der Tabelle in die Datenbank
type: docs
weight: 110
url: /de/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## FormDataConverter.ImportIntoDataBase Methode

Importiert Daten aus der Tabelle in die Datenbank.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connectString | String | Verbindungszeichenfolge der Datenbank. |
| dbType | DataType | Typ der Datenbankverbindung: OLEDB oder ODBC. |

## Beispiele

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

### Siehe auch

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)