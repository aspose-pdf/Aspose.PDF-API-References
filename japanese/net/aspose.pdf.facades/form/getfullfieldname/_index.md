---
title: "Form.GetFullFieldName"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。短いフィールド名に基づいて完全なフィールド名を取得します"
type: docs
weight: 250
url: /ja/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName method

短いフィールド名に従って完全なフィールド名を取得します。

```csharp
public string GetFullFieldName(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名。 |

### 戻り値

完全なフィールド名です。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


