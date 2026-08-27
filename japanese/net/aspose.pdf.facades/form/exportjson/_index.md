---
title: "Form.ExportJson"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。ドキュメント内のすべてのフィールドの内容を JSON ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。"
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson method

Document のすべてのフィールド内容を JSON ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputJsonStream | Stream | ドキュメントのフィールドデータが書き込まれる出力 JSON ストリームです。 |
| indented | Boolean | オプション。JSON 出力を読みやすくするためにインデントするかどうかを指定します。デフォルト値は true です。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


