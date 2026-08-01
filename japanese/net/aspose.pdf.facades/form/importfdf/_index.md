---
title: "Form.ImportFdf"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。fdf ファイルからフィールドの内容をインポートし、新しい pdf に配置します。"
type: docs
weight: 280
url: /ja/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

fdf ファイルからフィールドの内容をインポートし、新しい pdf に配置します。

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFdfStream | Stream | 入力 fdf ストリーム。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


