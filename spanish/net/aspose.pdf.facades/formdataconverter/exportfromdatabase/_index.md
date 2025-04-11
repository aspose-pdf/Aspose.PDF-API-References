---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: Método FormDataConverter. Exporta datos de la base de datos a la tabla
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## Método FormDataConverter.ExportFromDataBase

Exporta datos de la base de datos a la tabla.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| connectString | String | Cadena de conexión para la base de datos. |
| dbType | DataType | Tipo de conexión: OLEDB o ODBC. |

## Ejemplos

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

### Ver También

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)