---
title: "FormDataConverter.ExportFromDataBase"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormDataConverter. Mengekspor data dari basis data ke tabel"
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase method

Ekspor data dari basis data ke tabel.

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| connectString | String | String koneksi untuk basis data. |
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


