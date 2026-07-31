---
title: "FormDataConverter.ExportFromDataBase"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "FormDataConverter metodo. Esporta dati dal database nella tabella"
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase method

Esporta i dati dal database nella table.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connectString | String | Stringa di connessione per il database. |
| dbType | DataType | Tipo di connessione: OLEDB o ODBC. |

## Esempi

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

### Vedi anche

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


