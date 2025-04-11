---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter metodu. Verileri veritabanından tabloya aktarır
type: docs
weight: 100
url: /tr/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase metodu

Verileri veritabanından tabloya aktarır.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| connectString | String | Veritabanı için bağlantı dizesi. |
| dbType | DataType | Bağlantı türü: OLEDB veya ODBC. |

## Örnekler

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

### Ayrıca Bakınız

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)