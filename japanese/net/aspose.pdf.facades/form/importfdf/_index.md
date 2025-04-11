---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。fdfファイルからフィールドの内容をインポートし、新しいpdfに配置します。
type: docs
weight: 280
url: /ja/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf メソッド

fdfファイルからフィールドの内容をインポートし、新しいpdfに配置します。

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFdfStream | Stream | 入力fdfストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### 関連項目

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)