---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter メソッド。テーブル内のデータをストリームに変換します。
type: docs
weight: 90
url: /ja/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## FormDataConverter.ConvertToStreams メソッド

テーブル内のデータをストリームに変換します。

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destStream | Stream[] | データが保存されるストリーム。 |
| destType | DataType | 保存されるデータの型。有効な値は: XML, FDF, XFDF。 |

## 例

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
DataRow newrow = table.NewRow();
newrow["textField"] = "NEW DATA";
newrow["listboxField"] = "Item1";
newrow["comboboxField"] = "Item1";
newrow["checkboxField"] = "true";
newrow["radiobuttonField"] = "true";
table.Rows.Add(newrow);
fc.Table = table;
fc.ConvertToStreams(new Stream[] { stream }, DataType.XML);
```

### 関連項目

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)