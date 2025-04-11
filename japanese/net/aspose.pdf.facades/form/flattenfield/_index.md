---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。指定されたフィールドを完全修飾フィールド名でフラット化します。他のフィールドは変更されません。fieldNameが無効な場合、すべてのフィールドは変更されません。
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField メソッド

指定されたフィールドを完全修飾フィールド名でフラット化します。他のフィールドは変更されません。fieldNameが無効な場合、すべてのフィールドは変更されません。

```csharp
public void FlattenField(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | 文字列 | フラット化するフィールドの名前。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)