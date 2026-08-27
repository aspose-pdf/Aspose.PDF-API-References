---
title: "FormDataConverter.ImportIntoDataBase"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormDataConverter. Mengimpor data dari tabel ke basis data"
type: docs
weight: 110
url: /id/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## FormDataConverter.ImportIntoDataBase method

Impor data dari tabel ke basis data.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| connectString | String | String koneksi basis data. |
| dbType | DataType | Jenis koneksi basis data: OLEDB atau ODBC. |

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


