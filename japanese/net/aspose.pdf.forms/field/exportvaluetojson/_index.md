---
title: "Field.ExportValueToJson"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Field メソッド。指定されたフィールドの内容を JSON ストリームにエクスポートします。ボタン フィールドの値はエクスポートされません。"
type: docs
weight: 180
url: /ja/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson method

指定されたフィールドの内容を JSON ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputJsonStream | Stream | フィールド データが書き込まれる出力 JSON ストリーム。 |
| indented | Boolean | オプション。JSON 出力を読みやすくするためにインデントするかどうかを指定します。デフォルト値は true です。 |

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### 関連項目

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


