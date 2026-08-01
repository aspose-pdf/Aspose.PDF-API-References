---
title: "Form.ExportXml"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。PDF のフィールド内容を XML ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません"
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml method

PDF のフィールド内容を XML ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。

```csharp
public void ExportXml(Stream outputXmlStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputXmlStream | Stream | 出力 XML ストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


