---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter metodu. Tablo verilerini veritabanına aktarır
type: docs
weight: 110
url: /tr/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## FormDataConverter.ImportIntoDataBase metodu

Tablo verilerini veritabanına aktarır.

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| connectString | String | Veritabanının bağlantı dizesi. |
| dbType | DataType | Veritabanı bağlantı türü: OLEDB veya ODBC. |

## Örnekler

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

### Ayrıca Bakınız

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)