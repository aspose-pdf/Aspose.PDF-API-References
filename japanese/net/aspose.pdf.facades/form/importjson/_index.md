---
title: "Form.ImportJson"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。JSON ストリームからすべてのフィールドデータをインポートし、完全名で一致するドキュメントのフィールドにマッピングします。"
type: docs
weight: 290
url: /ja/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson method

JSON ストリームからすべてのフィールドデータをインポートし、完全な名前でフィールドを一致させて document フィールドに配置します。

```csharp
public void ImportJson(Stream inputJsonStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputJsonStream | Stream | ドキュメントのフィールドにインポートされるフィールドデータを含む入力 JSON ストリームです。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


