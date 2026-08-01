---
title: "DictionaryEditor.Remove"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "DictionaryEditor メソッド。指定されたキーを持つ要素を DictionaryEditor から削除します。"
type: docs
weight: 140
url: /ja/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

指定されたキーを持つ要素を [`DictionaryEditor`](../) から削除します。

```csharp
public bool Remove(string key)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| キー | String | 削除する要素のキー。 |

### 戻り値

要素が正常に削除された場合は true、そうでない場合は false を返します。このメソッドは、元の辞書にキーが見つからない場合やキーが編集不可の場合も false を返します。

### 関連項目

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

特定のオブジェクトの最初の出現を [`DictionaryEditor`](../) から削除します。

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| item | KeyValuePair`2 | [`DictionaryEditor`](../) から削除するオブジェクト。 |

### 戻り値

アイテムが [`DictionaryEditor`](../) から正常に削除された場合は true、そうでない場合は false を返します。このメソッドは、元の [`DictionaryEditor`](../) にアイテムが見つからない場合も false を返します。

### 関連項目

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


