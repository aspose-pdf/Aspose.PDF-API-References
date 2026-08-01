---
title: "Form.FieldNames"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form プロパティ。フォーム上のフィールド名のリストを取得します。"
type: docs
weight: 30
url: /ja/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames property

フォーム上のフィールド名のリストを取得します。

```csharp
public string[] FieldNames { get; }
```

## 例

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


