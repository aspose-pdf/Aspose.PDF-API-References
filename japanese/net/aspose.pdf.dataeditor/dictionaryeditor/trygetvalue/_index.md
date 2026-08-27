---
title: "DictionaryEditor.TryGetValue"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "DictionaryEditor メソッド。string、name、bool、number のような単純データ型へのアクセス用です。その他の型に対しては null を返します。"
type: docs
weight: 150
url: /ja/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor.TryGetValue method

文字列、名前、bool、数値などの単純データ型にアクセスするためです。他の型に対しては null を返します。

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| キー | String | キー値 |
| value | ICosPdfPrimitive& | キーに対して [`ICosPdfPrimitive`](../../icospdfprimitive/) を返すか、null を返します。 |

### 戻り値

`[`ICosPdfPrimitive`](../../icospdfprimitive/)` が string、name、bool、number のような場合は true を返します。その他のすべての型に対しては false を返します。

### 関連項目

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


