---
title: "ImageStamp"
linktitle: "ImageStamp"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "グラフィックスタンプを表します。"
type: docs
weight: 2360
url: /ja/java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

グラフィックスタンプを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | 新しい {@code ImageStamp} クラスのインスタンスを初期化します。 |
| [ImageStamp](#ImageStamp-java.lang.String-) | 指定されたファイルの画像で画像スタンプを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [close](#close--) | このインスタンスを閉じます |
| [getAlternativeText](#getAlternativeText--) | 画像スタンプの代替テキストを取得します。 |
| [getHeight](#getHeight--) | 画像の高さを取得します。この画像を設定すると、画像を垂直方向にスケールできます。 |
| [getImage](#getImage--) | スタンプに使用される画像ストリームを取得します。 |
| [getQuality](#getQuality--) | 画像スタンプの品質をパーセンテージで取得します。有効な値は 0..100% です。 |
| [getWidth](#getWidth--) | 画像の幅を取得します。このプロパティを設定すると、画像を水平方向にスケールできます。 |
| [getXIndent](#getXIndent--) | 左端から開始する水平スタンプ座標を取得および設定します。 |
| [getYIndent](#getYIndent--) | 下端から開始する垂直スタンプ座標を取得および設定します。 |
| [put](#put-com.aspose.pdf.Page-) | ページにグラフィックスタンプを追加します。 |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | 画像スタンプの代替テキストを設定します。 |
| [setHeight](#setHeight-double-) | 画像の高さを設定します。この画像を設定すると、画像を垂直方向にスケールできます。 |
| [setQuality](#setQuality-int-) | 画像スタンプの品質をパーセンテージで設定します。有効な値は 0..100% です。 |
| [setWidth](#setWidth-double-) | 画像の幅を設定します。このプロパティを設定すると、画像を水平方向にスケールできます。 |
| [setXIndent](#setXIndent-double-) | 左端から開始する水平スタンプ座標を取得および設定します。 |
| [setYIndent](#setYIndent-double-) | 下端から開始する垂直スタンプ座標を取得および設定します。 |

### ImageStamp {#ImageStamp-java.io.InputStream-}
新しい {@code ImageStamp} クラスのインスタンスを初期化します。

### ImageStamp {#ImageStamp-java.lang.String-}
指定されたファイルの画像で画像スタンプを作成します。

### close {#close--}
```
public void close()
```

このインスタンスを閉じます

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

画像スタンプの代替テキストを取得します。

**Returns:**
文字列値

### getHeight {#getHeight--}
```
public double getHeight()
```

画像の高さを取得します。この画像を設定すると、画像を垂直方向にスケールできます。

**Returns:**
double 値

### getImage {#getImage--}
```
public InputStream getImage()
```

スタンプに使用される画像ストリームを取得します。

**Returns:**
InputStream オブジェクト

### getQuality {#getQuality--}
```
public int getQuality()
```

画像スタンプの品質をパーセンテージで取得します。有効な値は 0..100% です。

**Returns:**
int 値です。

### getWidth {#getWidth--}
```
public double getWidth()
```

画像の幅を取得します。このプロパティを設定すると、画像を水平方向にスケールできます。

**Returns:**
double 値

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

左端から開始する水平スタンプ座標を取得および設定します。

**Returns:**
double 値

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

下端から開始する垂直スタンプ座標を取得および設定します。

**Returns:**
double 値

### put {#put-com.aspose.pdf.Page-}
ページにグラフィックスタンプを追加します。

### setAlternativeText {#setAlternativeText-java.lang.String-}
画像スタンプの代替テキストを設定します。

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

画像の高さを設定します。この画像を設定すると、画像を垂直方向にスケールできます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

画像スタンプの品質をパーセンテージで設定します。有効な値は 0..100% です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

画像の幅を設定します。このプロパティを設定すると、画像を水平方向にスケールできます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

左端から開始する水平スタンプ座標を取得および設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

下端から開始する垂直スタンプ座標を取得および設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |
