---
title: Metadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: メタデータメソッド。メタデータからエントリを削除します。
type: docs
weight: 200
url: /ja/net/aspose.pdf/metadata/remove/
---
## Remove(string) {#remove_1}

メタデータからエントリを削除します。

```csharp
public bool Remove(string key)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | String | 削除するエントリのキー。 |

### 戻り値

キーが削除された場合は true; それ以外の場合は false。

### 参照

* クラス [Metadata](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

コレクションからキー/値ペアを削除します。

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | KeyValuePair`2 | 削除されるキー/値ペア。 |

### 戻り値

ペアが見つかり、削除された場合は true。

### 参照

* クラス [XmpValue](../../xmpvalue/)
* クラス [Metadata](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)