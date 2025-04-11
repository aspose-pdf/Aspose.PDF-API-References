---
title: FormDataConverter.ExportFromDataBase
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter メソッド。データベースからテーブルにデータをエクスポートします。
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/formdataconverter/exportfromdatabase/
---
## FormDataConverter.ExportFromDataBase メソッド

データベースからテーブルにデータをエクスポートします。

```csharp
public void ExportFromDataBase(string connectString, DataType dbType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| connectString | String | データベースの接続文字列。 |
| dbType | DataType | 接続タイプ：OLEDB または ODBC。 |

## 例

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

### 参照

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)