---
title: "Form.FillBarcodeField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。完全修飾フィールド名に従ってバーコードフィールドに入力します。"
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

完全修飾フィールド名に従ってバーコードフィールドに入力します。

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名。 |
| data | String | 新しいバーコードの値です。 |

### 戻り値

入力が成功した場合は true を返し、そうでない場合は false を返します。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


