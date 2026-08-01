---
title: "Form.GetFieldLimit"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。テキストフィールドの制限を取得します"
type: docs
weight: 230
url: /ja/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

テキストフィールドの制限を取得します。

```csharp
public int GetFieldLimit(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名です。 |

### 戻り値

テキストフィールドに入力できる文字数の上限を返します。設定されていない場合は 0 を返します

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


