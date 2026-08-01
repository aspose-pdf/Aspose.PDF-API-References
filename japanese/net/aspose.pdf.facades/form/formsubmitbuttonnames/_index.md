---
title: "Form.FormSubmitButtonNames"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form プロパティ。すべてのフォーム送信ボタン名を取得します"
type: docs
weight: 40
url: /ja/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames property

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

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


