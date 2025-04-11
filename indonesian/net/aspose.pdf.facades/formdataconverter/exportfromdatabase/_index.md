---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: Metode FormDataConverter. Mengekspor data dari database ke tabel
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## Metode FormDataConverter.ExportFromDataBase

Mengekspor data dari database ke tabel.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| connectString | String | String koneksi untuk database. |
| dbType | DataType | Tipe koneksi: OLEDB atau ODBC. |

## Contoh

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

### Lihat Juga

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)