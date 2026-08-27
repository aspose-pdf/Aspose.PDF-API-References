---
title: "Form.ExportXfdf"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。PDF のフィールド内容を XML ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません"
type: docs
weight: 90
url: /ja/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf method

PDF のフィールド内容を XML ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputXfdfStream | Stream | 出力 xml ストリームです。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


