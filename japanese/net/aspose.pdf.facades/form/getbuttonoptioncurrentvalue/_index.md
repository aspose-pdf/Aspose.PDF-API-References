---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。ラジオボタンオプションフィールドの現在の値を返します
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue メソッド

ラジオボタンオプションフィールドの現在の値を返します。

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | フィールド名 |

### 戻り値

現在のラジオグループオプションの文字列値。 [`GetButtonOptionValues`](../getbuttonoptionvalues/) も参照してください。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)