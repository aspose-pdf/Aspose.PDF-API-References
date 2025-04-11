---
title: CosPdfDictionary.Item
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary プロパティ。指定されたキーを持つ要素を取得または設定します
type: docs
weight: 60
url: /ja/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## CosPdfDictionary インデクサ

指定されたキーを持つ要素を取得または設定します。

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| パラメータ | 説明 |
| --- | --- |
| key | 取得または設定する要素のキー。 |

### 戻り値

指定されたキーを持つ要素。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | キーが null です。 |
| KeyNotFoundException | プロパティが取得され、キーが見つかりません。 |
| ArgumentException | キーを編集または設定できない場合に例外をスローします。 |

### 参照

* インターフェース [ICosPdfPrimitive](../../icospdfprimitive/)
* クラス [CosPdfDictionary](../)
* 名前空間 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* アセンブリ [Aspose.PDF](../../../)