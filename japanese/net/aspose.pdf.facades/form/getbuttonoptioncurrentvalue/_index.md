---
title: "Form.GetButtonOptionCurrentValue"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。ラジオボタンオプションフィールドの現在の値を返します"
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue method

ラジオボタンオプションフィールドの現在の値を返します。

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | フィールド名 |

### 戻り値

現在のラジオグループオプションの文字列値。こちらも参照してください [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## 例

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


