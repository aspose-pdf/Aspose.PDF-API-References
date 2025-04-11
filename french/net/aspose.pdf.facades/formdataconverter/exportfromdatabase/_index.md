---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormDataConverter. Exporte des données de la base de données vers une table
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## Méthode FormDataConverter.ExportFromDataBase

Exporte des données de la base de données vers une table.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| connectString | String | Chaîne de connexion pour la base de données. |
| dbType | DataType | Type de connexion : OLEDB ou ODBC. |

## Exemples

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

### Voir aussi

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)