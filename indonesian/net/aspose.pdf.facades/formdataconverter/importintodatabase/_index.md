---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: Metode FormDataConverter. Mengimpor data dari tabel ke dalam database
type: docs
weight: 110
url: /id/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## Metode FormDataConverter.ImportIntoDataBase

Mengimpor data dari tabel ke dalam database.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| connectString | String | String koneksi database. |
| dbType | DataType | Tipe koneksi database: OLEDB atau ODBC. |

## Contoh

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

### Lihat Juga

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)