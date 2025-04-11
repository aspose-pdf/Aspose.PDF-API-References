---
title: CosPdfDictionary.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary メソッド。文字列、名前、ブール値、数値のような単純なデータ型にアクセスするためのもの。その他の型には null を返します。
type: docs
weight: 170
url: /ja/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary.TryGetValue メソッド

文字列、名前、ブール値、数値のような単純なデータ型にアクセスするためのもの。その他の型には null を返します。

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | String | キー値 |
| value | ICosPdfPrimitive& | キーに対して [`ICosPdfPrimitive`](../../icospdfprimitive/) を返すか、null を返します。 |

### 戻り値

[`ICosPdfPrimitive`](../../icospdfprimitive/) が文字列、名前、ブール値、数値のようなものであれば true を返します。その他のすべての型には false を返します。

### 参照

* インターフェース [ICosPdfPrimitive](../../icospdfprimitive/)
* クラス [CosPdfDictionary](../)
* 名前空間 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* アセンブリ [Aspose.PDF](../../../)