---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor メソッド。文字列、名前、ブール値、数値のような単純なデータ型にアクセスします。他の型には null を返します。
type: docs
weight: 150
url: /ja/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor.TryGetValue メソッド

文字列、名前、ブール値、数値のような単純なデータ型にアクセスします。他の型には null を返します。

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | String | キー値 |
| value | ICosPdfPrimitive& | キーに対して [`ICosPdfPrimitive`](../../icospdfprimitive/) を返すか、null を返します。 |

### 戻り値

[`ICosPdfPrimitive`](../../icospdfprimitive/) が文字列、名前、ブール値、数値のような場合は true を返します。他のすべての型には false を返します。

### 参照

* インターフェース [ICosPdfPrimitive](../../icospdfprimitive/)
* クラス [DictionaryEditor](../)
* 名前空間 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* アセンブリ [Aspose.PDF](../../../)