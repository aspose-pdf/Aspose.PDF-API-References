---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。完全修飾フィールド名に従ってバーコードフィールドを埋める
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField メソッド

完全修飾フィールド名に従ってバーコードフィールドを埋める。

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名。 |
| data | String | 新しいバーコード値。 |

### 戻り値

埋め込みが成功した場合は true を返し、そうでない場合は false を返す。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)