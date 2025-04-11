---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Form メソッド。短いフィールド名に基づいて完全なフィールド名を取得します。
type: docs
weight: 250
url: /ja/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName メソッド

短いフィールド名に基づいて完全なフィールド名を取得します。

```csharp
public string GetFullFieldName(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名。 |

### 戻り値

完全なフィールド名。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)