---
title: "FormDataConverter.ImportIntoDataBase"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "FormDataConverter méthode. Importe les données du tableau dans la base de données"
type: docs
weight: 110
url: /fr/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## FormDataConverter.ImportIntoDataBase method

Importe les données de la table vers la base de données.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| connectString | String | Chaîne de connexion de la base de données. |
| dbType | DataType | Type de connexion à la base de données : OLEDB ou ODBC. |

## Exemples

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

### Voir aussi

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


