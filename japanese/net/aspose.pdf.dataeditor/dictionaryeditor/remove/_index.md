---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor メソッド。指定されたキーを持つ要素を DictionaryEditor から削除します。
type: docs
weight: 140
url: /ja/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

指定されたキーを持つ要素を [`DictionaryEditor`](../) から削除します。

```csharp
public bool Remove(string key)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | String | 削除する要素のキー。 |

### 戻り値

要素が正常に削除された場合は true; それ以外の場合は false。このメソッドは、元の辞書にキーが見つからなかった場合や、キーが編集できない場合にも false を返します。

### 参照

* クラス [DictionaryEditor](../)
* 名前空間 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* アセンブリ [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

特定のオブジェクトの最初の出現を [`DictionaryEditor`](../) から削除します。

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | KeyValuePair`2 | [`DictionaryEditor`](../) から削除するオブジェクト。 |

### 戻り値

item が [`DictionaryEditor`](../) から正常に削除された場合は true; それ以外の場合は false。このメソッドは、item が元の [`DictionaryEditor`](../) に見つからなかった場合にも false を返します。

### 参照

* インターフェース [ICosPdfPrimitive](../../icospdfprimitive/)
* クラス [DictionaryEditor](../)
* 名前空間 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* アセンブリ [Aspose.PDF](../../../)