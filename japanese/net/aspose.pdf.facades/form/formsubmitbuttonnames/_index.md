---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: フォームプロパティ。すべてのフォーム送信ボタン名を取得します
type: docs
weight: 40
url: /ja/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames プロパティ

すべてのフォーム送信ボタン名を取得します。

```csharp
public string[] FormSubmitButtonNames { get; }
```

## 例

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)