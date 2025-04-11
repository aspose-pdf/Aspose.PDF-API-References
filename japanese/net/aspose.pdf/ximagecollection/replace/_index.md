---
title: XImageCollection.Replace
second_title: Aspose.PDF for .NET API Reference
description: XImageCollection メソッド。コレクション内の画像を別の画像に置き換えます
type: docs
weight: 150
url: /ja/net/aspose.pdf/ximagecollection/replace/
---
## Replace(int, Stream) {#replace}

コレクション内の画像を別の画像に置き換えます。

```csharp
public void Replace(int index, Stream stream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | [1..images count] 範囲内で置き換えられるコレクションアイテムのインデックス。 |
| stream | Stream | 画像データを含むストリーム（JPEG形式）。 |

### 参照

* クラス [XImageCollection](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_2}

コレクション内の画像を別の画像に置き換えます。

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | [1..images count] 範囲内で置き換えられるコレクションアイテムのインデックス。 |
| stream | Stream | 画像データを含むストリーム（JPEG形式）。 |
| quality | Int32 | JPEG圧縮の品質（パーセント）。有効な値は 0..100。 |
| isBlackAndWhite | Boolean | true の場合、画像は CCITT 圧縮方式で圧縮され、白黒画像に対してより良い圧縮を提供します。白黒画像のみに使用できます。 |

### 参照

* クラス [XImageCollection](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_1}

コレクション内の画像を別の画像に置き換えます。

```csharp
public void Replace(int index, Stream stream, int quality)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | [1..images count] 範囲内で置き換えられるコレクションアイテムのインデックス。 |
| stream | Stream | 画像データを含むストリーム（JPEG形式）。 |
| quality | Int32 | JPEG品質。 |

### 参照

* クラス [XImageCollection](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)