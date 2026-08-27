---
title: "CosPdfDictionary.Remove"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "CosPdfDictionary メソッド。指定されたキーを持つ要素を CosPdfDictionary から削除します"
type: docs
weight: 150
url: /ja/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

[`CosPdfDictionary`](../) から指定されたキーを持つ要素を削除します。

```csharp
public bool Remove(string key)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| キー | String | 削除する要素のキー。 |

### 戻り値

要素が正常に削除された場合は true、そうでない場合は false を返します。このメソッドは、元の辞書にキーが見つからない場合やキーが編集不可の場合も false を返します。

### 関連項目

* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

[`CosPdfDictionary`](../) から特定のオブジェクトの最初の出現を削除します。

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| item | KeyValuePair`2 | [`CosPdfDictionary`](../) から削除するオブジェクトです。 |

### 戻り値

[`CosPdfDictionary`](../) から項目が正常に削除された場合は true、そうでなければ false です。このメソッドは、元の [`CosPdfDictionary`](../) に項目が見つからない場合も false を返します。

### 関連項目

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


