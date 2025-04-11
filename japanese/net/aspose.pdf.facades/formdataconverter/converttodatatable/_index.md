---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter メソッド。ストリームのファイルをテーブルに変換します
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## FormDataConverter.ConvertToDataTable メソッド

ストリームのファイルをテーブルに変換します。

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceStreams | Stream[] | 指定された形式のソースストリームの配列。 |
| sourceType | DataType | ストリーム内のデータの形式。 有効な値は: PDF, FDF, XFDF, XML。 |

## 例

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
FormDataConverter fc = new FormDataConverter();
Stream stream = new FileStream("PdfWithAcroForm.pdf", FileMode.Open);
fc.Table = table;
fc.ConvertToDataTable(new Stream[] { stream }, DataType.PDF);
stream.Close();
```

### 関連項目

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)