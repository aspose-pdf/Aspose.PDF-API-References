---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Form メソッド。フィールド名に従ってフィールドの値を取得します
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField メソッド

フィールド名に従ってフィールドの値を取得します。

```csharp
public string GetField(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名。 |

### 戻り値

フィールドの値。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)