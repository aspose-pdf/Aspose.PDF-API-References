---
title: "Form.GetRichText"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。各文字の書式情報を含むリッチテキストフィールドの値を取得します。"
type: docs
weight: 260
url: /ja/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

リッチテキストフィールドの値を取得し、各文字の書式情報を含みます。

```csharp
public string GetRichText(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | リッチテキストフィールドの完全修飾フィールド名。 |

### 戻り値

リッチテキストフィールドの書式情報を含む文字列を返します。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


