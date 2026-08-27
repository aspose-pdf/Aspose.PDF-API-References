---
title: "DictionaryEditor.Item"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "DictionaryEditor プロパティ。指定されたキーを持つ要素を取得または設定します。"
type: docs
weight: 50
url: /ja/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## DictionaryEditor indexer

指定されたキーの要素を取得または設定します。

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| キー | 取得または設定する要素のキー。 |

### 戻り値

指定されたキーを持つ要素。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | キーが null です。 |
| KeyNotFoundException | プロパティが取得されましたが、キーが見つかりませんでした。 |
| ArgumentException | キーが編集または設定できない場合は例外をスローします。 |

### 関連項目

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


