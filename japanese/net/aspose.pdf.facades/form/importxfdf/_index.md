---
title: "Form.ImportXfdf"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。xfdfxml ファイルからフィールドの内容をインポートし、新しい pdf に配置します。"
type: docs
weight: 300
url: /ja/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

xfdf(xml) ファイルからフィールドの内容をインポートし、新しい pdf に配置します。

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputXfdfStream | Stream | 入力 xfdf(xml) ストリームです。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


