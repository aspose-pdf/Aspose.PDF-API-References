---
title: "Page.AddImage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Page メソッド。画像をページに追加し、指定された矩形の中央に配置して画像の比率を保持します。"
type: docs
weight: 350
url: /ja/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

画像をページに追加し、指定された矩形の中央に配置して、画像の比率を保持します。

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageStream | Stream | 画像のストリームです。 |
| imageRect | Rectangle | 画像の位置です。 |
| bbox | Rectangle | 画像の Bbbox。 |
| autoAdjustRectangle | Boolean | 入力矩形の中心に画像を調整します。 |

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

検索可能な画像をページに追加し、指定された矩形の中央に配置して、画像の比率を保持します。

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| hocr | String | 画像の hocr。 |
| imageStream | Stream | 画像のストリームです。 |
| imageRect | Rectangle | 画像の位置です。 |
| bbox | Rectangle | 画像の bbox。 |

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

ページに画像を追加し、画像の矩形位置に応じて配置します。

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imageStream | Stream | 画像のストリームです。 |
| imageRect | Rectangle | ページ上の画像のデフォルト位置です。 |
| imageWidth | Int32 | 画像の幅です。 |
| imageHeight | Int32 | 画像の高さです。 |
| saveImageProportions | Boolean | フラグが true に設定されている場合、画像は矩形の位置に配置されます。そうでない場合、矩形のサイズは画像サイズと同じになります。 |
| bbox | Rectangle | 画像の bbox。 |

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

画像をページに追加し、指定された矩形の中央に配置して、画像の比率を保持します。

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| imagePath | String | 画像へのパスです。 |
| rectangle | Rectangle | 画像の位置です。 |

### 関連項目

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


