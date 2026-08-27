---
title: "Image"
linktitle: "Image"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "画像を表します"
type: docs
weight: 2280
url: /ja/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

画像を表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Image](#Image--) | デフォルトコンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | bmp/png/gif/tiff 画像を JPG 形式の画像ストリームに変換しようとします。 |
| [deepClone](#deepClone--) | 画像をクローンします。 |
| [getBitmapInfo](#getBitmapInfo--) | 圧縮されていない画像バイトを取得または設定します。 |
| [getBitmapSize](#getBitmapSize--) | 画像のビットマップサイズを取得します。 |
| [getBufferedImage](#getBufferedImage--) | java awt 画像を取得します。 |
| [getFile](#getFile--) | 画像ファイルを取得します。 |
| [getFileType](#getFileType--) | 画像ファイルのタイプを取得します。 |
| [getFixHeight](#getFixHeight--) | 画像の高さを取得します。 |
| [getFixWidth](#getFixWidth--) | 画像の幅を取得します。 |
| [getImageScale](#getImageScale--) | 画像のスケールを取得します。 |
| [getImageStream](#getImageStream--) | 画像ストリームを取得します。 |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | 画像の MIME タイプを返します。 |
| [getTitle](#getTitle--) | 画像のタイトルを示す文字列値を取得します。 |
| [isApplyResolution](#isApplyResolution--) | 画像生成時に解像度を使用するかどうかを示すブール値を取得または設定します |
| [isBlackWhite](#isBlackWhite--) | 画像が白黒に強制されるかどうかを示すブール値を取得します。TIFF 画像が CCITT サブフォーマットの場合、このプロパティは true に設定する必要があります。 |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | グレースケール画像に対して 1bpp エンコーディングを検出して使用しようとします。デフォルト値 == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | 画像生成時に解像度を使用するかどうかを示すブール値を取得または設定します |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | 圧縮されていない画像バイトを取得または設定します。 |
| [setBlackWhite](#setBlackWhite-boolean-) | 画像が白黒に強制されるかどうかを示すブール値を設定します。TIFF 画像が CCITT サブフォーマットの場合、このプロパティは true に設定する必要があります。 |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | グレースケール画像に対して 1bpp エンコーディングを検出して使用しようとします。デフォルト値 == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | java awt 画像を設定します。 |
| [setFile](#setFile-java.lang.String-) | 画像ファイルを設定します。 |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | 画像ファイルのタイプを設定します。 |
| [setFixHeight](#setFixHeight-double-) | 画像の高さを設定します。 |
| [setFixWidth](#setFixWidth-double-) | 画像の幅を設定します。 |
| [setImageScale](#setImageScale-double-) | 画像のスケールを設定します。 |
| [setImageStream](#setImageStream-java.io.InputStream-) | 画像ストリームを設定します。 |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | 画像のタイトルを示す文字列値を設定します。 |

### Image {#Image--}
```
public Image()
```

デフォルトコンストラクタ

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
bmp/png/gif/tiff 画像を JPG 形式の画像ストリームに変換しようとします。

### deepClone {#deepClone--}
```
public Object deepClone()
```

画像をクローンします。

**Returns:**
クローンされたオブジェクト

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

圧縮されていない画像バイトを取得または設定します。

**Returns:**
BitmapInfo インスタンス

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

画像のビットマップサイズを取得します。

**Returns:**
矩形インスタンス

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

java awt 画像を取得します。

**Returns:**
BufferedImage オブジェクト

### getFile {#getFile--}
```
public String getFile()
```

画像ファイルを取得します。

**Returns:**
文字列値

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

画像ファイルのタイプを取得します。

**Returns:**
int 値 @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

画像の高さを取得します。

**Returns:**
double 値

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

画像の幅を取得します。

**Returns:**
double 値

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

画像のスケールを取得します。

**Returns:**
double 値

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

画像ストリームを取得します。

**Returns:**
InputStream オブジェクト

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
画像の MIME タイプを返します。

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

画像のタイトルを示す文字列値を取得します。

**Returns:**
TextFragment の値

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

画像生成時に解像度を使用するかどうかを示すブール値を取得または設定します

**Returns:**
ブール値

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

画像が白黒に強制されるかどうかを示すブール値を取得します。TIFF 画像が CCITT サブフォーマットの場合、このプロパティは true に設定する必要があります。

**Returns:**
ブール値

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

グレースケール画像に対して 1bpp エンコーディングを検出して使用しようとします。デフォルト値 == FALSE

**Returns:**
ブール値

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

画像生成時に解像度を使用するかどうかを示すブール値を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
圧縮されていない画像バイトを取得または設定します。

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

画像が白黒に強制されるかどうかを示すブール値を設定します。TIFF 画像が CCITT サブフォーマットの場合、このプロパティは true に設定する必要があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

グレースケール画像に対して 1bpp エンコーディングを検出して使用しようとします。デフォルト値 == FALSE

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| blackWhiteForGrayScale |  | ブール値 |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
java awt 画像を設定します。

### setFile {#setFile-java.lang.String-}
画像ファイルを設定します。

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
画像ファイルのタイプを設定します。

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

画像の高さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

画像の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

画像のスケールを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setImageStream {#setImageStream-java.io.InputStream-}
画像ストリームを設定します。

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
画像のタイトルを示す文字列値を設定します。
