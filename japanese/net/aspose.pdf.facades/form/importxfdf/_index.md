---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。xfdfxmlファイルからフィールドの内容をインポートし、新しいpdfに配置します。
type: docs
weight: 300
url: /ja/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf メソッド

xfdf(xml)ファイルからフィールドの内容をインポートし、新しいpdfに配置します。

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputXfdfStream | Stream | 入力xfdf(xml)ストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### 関連項目

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)