---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。PDFのフィールドの内容をFDFストリームにエクスポートします。
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf メソッド

PDFのフィールドの内容をFDFストリームにエクスポートします。

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFdfStream | Stream | 出力FDFストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)