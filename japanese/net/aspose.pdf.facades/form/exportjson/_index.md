---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。ドキュメント内のすべてのフィールドの内容をJSONストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson メソッド

ドキュメント内のすべてのフィールドの内容をJSONストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputJsonStream | Stream | ドキュメントのフィールドデータが書き込まれる出力JSONストリーム。 |
| indented | Boolean | オプション。JSON出力をより読みやすくするためにインデントするかどうかを指定します。デフォルト値はtrueです。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)