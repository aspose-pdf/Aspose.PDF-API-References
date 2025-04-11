---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter-Methode. Exportiert Daten aus der Datenbank in eine Tabelle
type: docs
weight: 100
url: /de/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase-Methode

Exportiert Daten aus der Datenbank in eine Tabelle.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connectString | String | Verbindungszeichenfolge für die Datenbank. |
| dbType | DataType | Verbindungstyp: OLEDB oder ODBC. |

## Beispiele

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

### Siehe auch

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)