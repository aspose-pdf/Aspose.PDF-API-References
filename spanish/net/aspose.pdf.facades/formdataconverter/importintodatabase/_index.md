---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: Método FormDataConverter. Importa datos de la tabla a la base de datos
type: docs
weight: 110
url: /es/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## Método FormDataConverter.ImportIntoDataBase

Importa datos de la tabla a la base de datos.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| connectString | String | Cadena de conexión de la base de datos. |
| dbType | DataType | Tipo de conexión a la base de datos: OLEDB o ODBC. |

## Ejemplos

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

### Ver También

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)