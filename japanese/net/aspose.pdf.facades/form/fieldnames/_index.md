---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: フォームプロパティ。フォーム上のフィールド名のリストを取得します
type: docs
weight: 30
url: /ja/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames プロパティ

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

### 参照

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)