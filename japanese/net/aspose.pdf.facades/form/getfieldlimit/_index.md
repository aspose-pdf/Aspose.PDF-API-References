---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。テキストフィールドの制限を取得します。
type: docs
weight: 230
url: /ja/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit メソッド

テキストフィールドの制限を取得します。

```csharp
public int GetFieldLimit(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | 文字列 | 資格のあるフィールド名。 |

### 戻り値

テキストフィールドに入力できる文字数の制限を返します。設定されていない場合は、0を返します。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)