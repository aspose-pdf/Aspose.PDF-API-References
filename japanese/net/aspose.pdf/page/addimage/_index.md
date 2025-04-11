---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Page メソッド。指定された矩形の中央に画像を追加し、画像の比率を保存します。
type: docs
weight: 350
url: /ja/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

指定された矩形の中央に画像を追加し、画像の比率を保存します。

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageStream | Stream | 画像のストリーム。 |
| imageRect | Rectangle | 画像の位置。 |
| bbox | Rectangle | 画像のバウンディングボックス。 |
| autoAdjustRectangle | Boolean | 入力矩形の中央に画像を調整します。 |

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

検索可能な画像をページに追加し、指定された矩形の中央に画像を配置して画像の比率を保存します。

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hocr | String | 画像の hocr。 |
| imageStream | Stream | 画像のストリーム。 |
| imageRect | Rectangle | 画像の位置。 |
| bbox | Rectangle | 画像のバウンディングボックス。 |

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

ページに画像を追加し、画像の矩形位置に基づいて配置します。

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageStream | Stream | 画像のストリーム。 |
| imageRect | Rectangle | ページ上の画像のデフォルト位置。 |
| imageWidth | Int32 | 画像の幅。 |
| imageHeight | Int32 | 画像の高さ。 |
| saveImageProportions | Boolean | フラグが true に設定されている場合、画像は矩形の位置に配置されます。そうでない場合、矩形のサイズは画像のサイズと等しくなります。 |
| bbox | Rectangle | 画像のバウンディングボックス。 |

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

ページに画像を追加し、指定された矩形の中央に画像を配置して画像の比率を保存します。

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imagePath | String | 画像へのパス。 |
| rectangle | Rectangle | 画像の位置。 |

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)