---
title: DictionaryEditor.Item
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor プロパティ。指定されたキーを持つ要素を取得または設定します
type: docs
weight: 50
url: /ja/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## DictionaryEditor インデクサー

指定されたキーを持つ要素を取得または設定します。

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| key | 取得または設定する要素のキー。 |

### 戻り値

指定されたキーを持つ要素。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | キーが null です。 |
| KeyNotFoundException | プロパティが取得され、キーが見つかりません。 |
| ArgumentException | キーが編集または設定できない場合に例外をスローします。 |

### 参照

* インターフェース [ICosPdfPrimitive](../../icospdfprimitive/)
* クラス [DictionaryEditor](../)
* 名前空間 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* アセンブリ [Aspose.PDF](../../../)