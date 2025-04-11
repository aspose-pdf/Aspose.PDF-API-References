---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。フィールド名に基づいてラジオボタンオプションフィールドと関連値を取得します。このメソッドはラジオボタングループに意味があります。
type: docs
weight: 190
url: /ja/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues メソッド

フィールド名に基づいてラジオボタンオプションフィールドと関連値を取得します。このメソッドはラジオボタングループに意味があります。

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | 文字列 | フィールド名 |

### 戻り値

フォームアイテム名でキー付けされたオプション値のハッシュテーブル

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### 関連項目

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)