---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormDataConverter. Importa dati dalla tabella nel database
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## Metodo FormDataConverter.ImportIntoDataBase

Importa dati dalla tabella nel database.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connectString | String | Stringa di connessione del database. |
| dbType | DataType | Tipo di connessione al database: OLEDB o ODBC. |

## Esempi

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

### Vedi Anche

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)