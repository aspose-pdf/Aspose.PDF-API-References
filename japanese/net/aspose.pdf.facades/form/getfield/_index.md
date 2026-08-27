---
title: "Form.GetField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。フィールド名に従ってフィールドの値を取得します。"
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

フィールド名に従ってフィールドの値を取得します。

```csharp
public string GetField(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名。 |

### 戻り値

フィールドの値です。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


