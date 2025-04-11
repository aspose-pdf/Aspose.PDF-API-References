---
title: FormDataConverter.ImportIntoDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter メソッド。テーブルからデータをデータベースにインポートします
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/formdataconverter/importintodatabase/
---
## FormDataConverter.ImportIntoDataBase メソッド

テーブルからデータをデータベースにインポートします。

```csharp
public void ImportIntoDataBase(string connectString, DataType dbType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| connectString | String | データベースの接続文字列。 |
| dbType | DataType | データベース接続のタイプ：OLEDB または ODBC。 |

## 例

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

### 関連項目

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)