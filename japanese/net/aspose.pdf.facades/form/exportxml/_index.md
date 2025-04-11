---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Form メソッド。pdf のフィールドの内容を xml ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml メソッド

pdf のフィールドの内容を xml ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。

```csharp
public void ExportXml(Stream outputXmlStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputXmlStream | Stream | 出力 Xml ストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### 関連項目

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)