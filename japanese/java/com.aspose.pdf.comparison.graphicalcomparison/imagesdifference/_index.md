---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "2 つの PDF ページを比較した結果クラスを表します。"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

2 つの PDF ページを比較した結果クラスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | 指定された色を使用して差分配列をビットマップ画像に変換します。 |
| [dispose](#dispose--) | オブジェクトが破棄される前に、必要なクリーンアップ操作を実行します。 |
| [getDestinationImage](#getDestinationImage--) | 差分配列をソース画像に適用して、宛先画像を表す新しいビットマップを返します。 |
| [getDifference](#getDifference--) | 差分配列を取得します。この配列は、LockBits メソッドの結果として取得された元画像データ配列に似ています。 |
| [getHeight](#getHeight--) | 差分の高さ。 |
| [getSourceImage](#getSourceImage--) | 最初に比較されたページの画像を取得します。画像のピクセルフォーマットは 24bpp です。 |
| [getStride](#getStride--) | 差分画像データのストライド。 |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
指定された色を使用して差分配列をビットマップ画像に変換します。

### dispose {#dispose--}
```
public final void dispose()
```

オブジェクトが破棄される前に、必要なクリーンアップ操作を実行します。

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

差分配列をソース画像に適用して、宛先画像を表す新しいビットマップを返します。

**Returns:**
宛先画像。

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

差分配列を取得します。この配列は、LockBits メソッドの結果として取得された元画像データ配列に似ています。

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

差分の高さ。

**Returns:**
int 値です。

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

最初に比較されたページの画像を取得します。画像のピクセルフォーマットは 24bpp です。

**Returns:**
BufferedImage インスタンス

### getStride {#getStride--}
```
public final int getStride()
```

差分画像データのストライド。

**Returns:**
int 値です。
