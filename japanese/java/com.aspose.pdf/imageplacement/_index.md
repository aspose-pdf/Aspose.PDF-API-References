---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> PDF ドキュメントページに配置された画像の特性を表します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページ上の画像を検索し、画像を取得する方法を示しています。"
type: docs
weight: 2330
url: /ja/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> PDF ドキュメントページに配置された画像の特性を表します。 </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> 画像がページに配置されると、{@code Resources} で定義された物理的な寸法とは異なる寸法を持つ場合があります。オブジェクト {@code ImagePlacement} は、寸法や解像度などの情報を提供することを目的としています。 </p>

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | ページに配置された画像に対してアクティブなグラフィックス状態の合成パラメータを取得します。 |
| [getImage](#getImage--) | 関連する XImage リソースオブジェクトを取得します。 |
| [getMatrix](#getMatrix--) | この画像の現在の変換行列。 |
| [getOperator](#getOperator--) | 画像の表示に使用されるオペレーター。 |
| [getPage](#getPage--) | 画像が含まれるページを取得します。 |
| [getRectangle](#getRectangle--) | 画像の矩形を取得します。 |
| [getResolution](#getResolution--) | 画像の解像度を取得します。 |
| [getRotation](#getRotation--) | 画像の回転角度を取得します。 |
| [hide](#hide--) | ページから画像を削除します。 |
| [replace](#replace-java.io.InputStream-) | コレクション内の画像を別の画像に置き換えます。 |
| [save](#save-java.io.OutputStream-) | 画像を対応する変換（スケーリング、回転、解像度）とともに保存します。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | 画像を対応する変換（スケーリング、回転、解像度）とともに保存します。 |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

ページに配置された画像に対してアクティブなグラフィックス状態の合成パラメータを取得します。

**Returns:**
CompositingParameters オブジェクト

### getImage {#getImage--}
```
public XImage getImage()
```

関連する XImage リソースオブジェクトを取得します。

**Returns:**
XImage オブジェクト

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

この画像の現在の変換行列。

**Returns:**
Matrix オブジェクト

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

画像の表示に使用されるオペレーター。

**Returns:**
Operator インスタンス

### getPage {#getPage--}
```
public Page getPage()
```

画像が含まれるページを取得します。

**Returns:**
Page オブジェクト

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

画像の矩形を取得します。

**Returns:**
Rectangle オブジェクト

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

画像の解像度を取得します。

**Returns:**
Resolution オブジェクト

### getRotation {#getRotation--}
```
public float getRotation()
```

画像の回転角度を取得します。

**Returns:**
int 値です。

### hide {#hide--}
```
public final void hide()
```

ページから画像を削除します。

### replace {#replace-java.io.InputStream-}
コレクション内の画像を別の画像に置き換えます。

### save {#save-java.io.OutputStream-}
画像を対応する変換（スケーリング、回転、解像度）とともに保存します。

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
画像を対応する変換（スケーリング、回転、解像度）とともに保存します。
