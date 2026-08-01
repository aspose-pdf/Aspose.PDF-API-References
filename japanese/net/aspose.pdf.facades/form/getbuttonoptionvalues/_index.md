---
title: "Form.GetButtonOptionValues"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。フィールド名に基づいてラジオボタンのオプションフィールドと関連する値を取得します。このメソッドはラジオボタングループに対して意味があります。"
type: docs
weight: 190
url: /ja/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

フィールド名に基づいてラジオボタンオプションフィールドと関連する値を取得します。このメソッドはラジオボタングループに対して意味があります。

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | フィールド名 |

### 戻り値

フォーム項目名をキーとしたオプション値のハッシュテーブルです。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


