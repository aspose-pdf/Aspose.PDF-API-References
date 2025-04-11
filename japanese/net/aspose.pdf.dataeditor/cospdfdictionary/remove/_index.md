---
title: CosPdfDictionary.Remove
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary メソッド。指定されたキーを持つ要素を CosPdfDictionary から削除します。
type: docs
weight: 150
url: /ja/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

指定されたキーを持つ要素を [`CosPdfDictionary`](../) から削除します。

```csharp
public bool Remove(string key)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | String | 削除する要素のキー。 |

### 戻り値

要素が正常に削除された場合は true; それ以外の場合は false。このメソッドは、元の辞書にキーが見つからなかった場合や、キーが編集不可能な場合にも false を返します。

### 参照

* クラス [CosPdfDictionary](../)
* 名前空間 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* アセンブリ [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

特定のオブジェクトの最初の出現を [`CosPdfDictionary`](../) から削除します。

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | KeyValuePair`2 | [`CosPdfDictionary`](../) から削除するオブジェクト。 |

### 戻り値

item が [`CosPdfDictionary`](../) から正常に削除された場合は true; それ以外の場合は false。このメソッドは、item が元の [`CosPdfDictionary`](../) に見つからなかった場合にも false を返します。

### 参照

* インターフェース [ICosPdfPrimitive](../../icospdfprimitive/)
* クラス [CosPdfDictionary](../)
* 名前空間 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* アセンブリ [Aspose.PDF](../../../)