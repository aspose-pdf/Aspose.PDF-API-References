---
title: "Form.ExportFdf"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。pdf のフィールド内容を fdf ストリームにエクスポートします。"
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf method

PDF のフィールド内容を fdf ストリームにエクスポートします。

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFdfStream | Stream | 出力 fdf ストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


