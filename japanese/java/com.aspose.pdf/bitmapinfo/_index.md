---
title: "BitmapInfo"
linktitle: "BitmapInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ピクセルの配列とビットマップ情報を含むオブジェクト。"
type: docs
weight: 300
url: /ja/java/com.aspose.pdf/bitmapinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BitmapInfo

```
public class BitmapInfo extends Object
```

ピクセルの配列とビットマップ情報を含むオブジェクト。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BitmapInfo](#BitmapInfo-byte:A-int-int-int-) | クラスの新しいインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFormat](#getFormat--) | ビットマップのピクセル形式を取得します。 |
| [getHeight](#getHeight--) | ビットマップの高さを取得します。 |
| [getPixelBytes](#getPixelBytes--) | ピクセルの配列を取得します。 |
| [getWidth](#getWidth--) | ビットマップの幅を取得します。 |

### BitmapInfo {#BitmapInfo-byte:A-int-int-int-}
```
public BitmapInfo(byte[] pixelBytes, int width, int height, int format)
```

クラスの新しいインスタンスを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixelBytes |  | ピクセルの配列です。 |
| 幅 |  | ビットマップの幅です。 |
| 高さ |  | ビットマップの高さです。 |
| フォーマット |  | ビットマップのピクセルフォーマットです。 @see BitmapInfo |

### getFormat {#getFormat--}
```
public final int getFormat()
```

ビットマップのピクセル形式を取得します。

**Returns:**
int 値 PixelFormat 要素

### getHeight {#getHeight--}
```
public final int getHeight()
```

ビットマップの高さを取得します。

**Returns:**
int 値です。

### getPixelBytes {#getPixelBytes--}
```
public final byte[] getPixelBytes()
```

ピクセルの配列を取得します。

**Returns:**
byte[] 配列

### getWidth {#getWidth--}
```
public final int getWidth()
```

ビットマップの幅を取得します。

**Returns:**
int 値です。
