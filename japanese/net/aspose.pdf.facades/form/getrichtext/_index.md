---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。すべての文字のフォーマット情報を含むリッチテキストフィールドの値を取得します。
type: docs
weight: 260
url: /ja/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText メソッド

リッチテキストフィールドの値を取得し、すべての文字のフォーマット情報を含みます。

```csharp
public string GetRichText(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | リッチテキストフィールドの完全修飾フィールド名。 |

### 戻り値

リッチテキストフィールドのフォーマット情報を含む文字列を返します。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)