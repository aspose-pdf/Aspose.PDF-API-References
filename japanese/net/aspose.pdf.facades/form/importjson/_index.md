---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。JSON ストリームからすべてのフィールドデータをインポートし、フィールドの完全な名前で一致するドキュメントフィールドに配置します。
type: docs
weight: 290
url: /ja/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson メソッド

JSON ストリームからすべてのフィールドデータをドキュメントフィールドにインポートし、フィールドの完全な名前で一致させます。

```csharp
public void ImportJson(Stream inputJsonStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputJsonStream | Stream | ドキュメントフィールドにインポートするフィールドデータを含む入力 JSON ストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)