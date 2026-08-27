---
title: "XImageCollection.Add"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "XImageCollection メソッド。新しい画像を Image リストに追加します。このメソッドは画像を同じ PdfObject への参照として追加し、ファイルサイズの削減を可能にします"
type: docs
weight: 70
url: /ja/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

画像リストに新しい画像を追加します。このメソッドは画像を同じ PdfObject への参照として追加し、ファイルサイズの削減を可能にします。

```csharp
public string Add(XImage image)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 画像 | XImage | 追加する XImage。 |

### 戻り値

追加された画像の名前。

### 関連項目

* class [XImage](../../ximage/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

エンティティをコレクションの末尾に追加し、最後のインデックスでアクセスできるようにします。

```csharp
public string Add(Stream image)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 画像 | Stream | 画像データ（JPEG 形式）のストリーム。 |

### 戻り値

追加された画像の名前。

### 関連項目

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

エンティティをコレクションの末尾に追加し、最後のインデックスでアクセスできるようにします。

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | ピクセルの配列とビットマップ情報（Width、Height、PixelFormat）を含むオブジェクト。 |

### 戻り値

追加された画像の名前。

### 関連項目

* class [BitmapInfo](../../bitmapinfo/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

エンティティをコレクションの末尾に追加し、最後のインデックスでアクセスできるようにします。

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 画像 | Stream | 画像データを含むストリーム。 |
| filterType | ImageFilterType | 画像フィルタのタイプです。 |

### 戻り値

追加された画像の名前。

### 関連項目

* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

エンティティをコレクションの末尾に追加し、最後のインデックスでアクセスできるようにします。

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | ピクセルの配列とビットマップ情報（Width、Height、PixelFormat）を含むオブジェクト。 |
| filterType | ImageFilterType | 画像フィルタのタイプです。 |

### 戻り値

追加された画像の名前。

### 関連項目

* class [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

エンティティをコレクションの末尾に追加し、最後のインデックスでアクセスできるようにします。

```csharp
public void Add(Stream image, int quality)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 画像 | Stream | 画像データ（JPEG 形式）のストリーム。 |
| quality | Int32 | JPEG の品質。 |

### 関連項目

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


