---
title: ExportFromDataBase
second_title: Aspose.PDF for .NET API Referansı
description: Verileri veritabanından tabloya aktarır.
type: docs
weight: 100
url: /tr/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase method

Verileri veritabanından tabloya aktarır.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connectString | String | Veritabanı için bağlantı dizesi. |
| dbType | DataType | Bağlantı türü: OLEDB veya ODBC. |

### Örnekler

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

### Ayrıca bakınız

* enum [DataType](../../datatype)
* class [FormDataConverter](../../formdataconverter)
* ad alanı [Aspose.Pdf.Facades](../../formdataconverter)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
