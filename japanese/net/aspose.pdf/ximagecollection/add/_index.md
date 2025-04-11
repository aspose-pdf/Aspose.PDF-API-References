---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: XImageCollection メソッド。画像リストに新しい画像を追加します。このメソッドは、同じ PdfObject への参照として画像を追加し、ファイルサイズを減少させることができます。
type: docs
weight: 70
url: /ja/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

画像リストに新しい画像を追加します。このメソッドは、同じ PdfObject への参照として画像を追加し（ファイルサイズを減少させることができます）、

```csharp
public string Add(XImage image)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | XImage | 追加される XImage。 |

### 戻り値

追加された画像の名前。

### 参照

* class [XImage](../../ximage/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

コレクションの末尾にエンティティを追加し、エンティティは最後のインデックスでアクセスできます。

```csharp
public string Add(Stream image)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Stream | 画像データを含むストリーム（JPEG形式）。 |

### 戻り値

追加された画像の名前。

### 参照

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

コレクションの末尾にエンティティを追加し、エンティティは最後のインデックスでアクセスできます。

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | ピクセルの配列とビットマップ情報（幅、高さ、ピクセル形式）を含むオブジェクト。 |

### 戻り値

追加された画像の名前。

### 参照

* class [BitmapInfo](../../bitmapinfo/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

コレクションの末尾にエンティティを追加し、エンティティは最後のインデックスでアクセスできます。

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Stream | 画像データを含むストリーム。 |
| filterType | ImageFilterType | 画像フィルターの種類。 |

### 戻り値

追加された画像の名前。

### 参照

* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

コレクションの末尾にエンティティを追加し、エンティティは最後のインデックスでアクセスできます。

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | ピクセルの配列とビットマップ情報（幅、高さ、ピクセル形式）を含むオブジェクト。 |
| filterType | ImageFilterType | 画像フィルターの種類。 |

### 戻り値

追加された画像の名前。

### 参照

* class [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

コレクションの末尾にエンティティを追加し、エンティティは最後のインデックスでアクセスできます。

```csharp
public void Add(Stream image, int quality)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Stream | 画像データを含むストリーム（JPEG形式）。 |
| quality | Int32 | JPEG品質。 |

### 参照

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)