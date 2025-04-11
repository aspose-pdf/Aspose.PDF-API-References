---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。pdfのフィールドの内容をxmlストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。
type: docs
weight: 90
url: /ja/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf メソッド

pdfのフィールドの内容をxmlストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputXfdfStream | ストリーム | 出力xmlストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)