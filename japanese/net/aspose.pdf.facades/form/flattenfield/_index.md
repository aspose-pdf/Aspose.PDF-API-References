---
title: "Form.FlattenField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。完全修飾フィールド名で指定されたフィールドをフラット化します。他のフィールドは変更できません。fieldName が無効な場合、すべてのフィールドは変更できません。"
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField method

完全修飾フィールド名で指定されたフィールドをフラット化します。他のフィールドは変更できないまま残ります。fieldName が無効な場合、すべてのフィールドは変更できないまま残ります。

```csharp
public void FlattenField(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | フラット化されるフィールドの名前。 |

## 例

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


