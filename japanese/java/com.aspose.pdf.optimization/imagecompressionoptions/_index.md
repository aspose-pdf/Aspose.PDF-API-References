---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "クラスは画像圧縮の設定オプションを含みます。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

クラスは画像圧縮の設定オプションを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEncoding](#getEncoding--) | 画像を保存するために使用されるエンコーディングを取得または設定します。 |
| [getImageQuality](#getImageQuality--) | CompressImages フラグが使用されている場合の画像圧縮レベルを指定します。 |
| [getMaxResolution](#getMaxResolution--) | 画像の最大解像度を指定します。画像の解像度がこれより高い場合はスケーリングされます。 |
| [getResizeImages](#getResizeImages--) | このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメーターより大きいときに画像がリサイズされます。 |
| [getVersion](#getVersion--) | 圧縮アルゴリズムのバージョン。可能な値は次のとおりです：1. 標準圧縮、2. 高速（標準よりも高速な改良圧縮ですが、すべての画像に適用できるわけではありません）、3. 混合（高速アルゴリズムで圧縮できない画像に標準圧縮が適用されます。これにより最高の圧縮が得られますが、\"高速\" アルゴリズムよりも遅くなります。バージョン \"Fast\" は画像のリサイズには適用できません（標準の方法が使用されます）。デフォルトは \"Standard\" です。 |
| [isCompressImages](#isCompressImages--) | このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定します。 |
| [setCompressImages](#setCompressImages-boolean-) | このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定します。 |
| [setEncoding](#setEncoding-int-) | 画像を保存するために使用されるエンコーディングを取得または設定します。 |
| [setImageQuality](#setImageQuality-int-) | CompressImages フラグが使用されている場合の画像圧縮レベルを指定します。 |
| [setMaxResolution](#setMaxResolution-int-) | 画像の最大解像度を指定します。画像の解像度がこれより高い場合はスケーリングされます。 |
| [setResizeImages](#setResizeImages-boolean-) | このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメーターより大きいときに画像がリサイズされます。 |
| [setVersion](#setVersion-int-) | 圧縮アルゴリズムのバージョン。可能な値は次のとおりです：1. 標準圧縮、2. 高速（標準よりも高速な改良圧縮ですが、すべての画像に適用できるわけではありません）、3. 混合（高速アルゴリズムで圧縮できない画像に標準圧縮が適用されます。これにより最高の圧縮が得られますが、\"高速\" アルゴリズムよりも遅くなります。バージョン \"Fast\" は画像のリサイズには適用できません（標準の方法が使用されます）。デフォルトは \"Standard\" です。 |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

画像を保存するために使用されるエンコーディングを取得または設定します。

**Returns:**
ImageEncoding 要素です。

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

CompressImages フラグが使用されている場合の画像圧縮レベルを指定します。

**Returns:**
int 値です。

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

画像の最大解像度を指定します。画像の解像度がこれより高い場合はスケーリングされます。

**Returns:**
int 値です。

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメーターより大きいときに画像がリサイズされます。

**Returns:**
ブール値

### getVersion {#getVersion--}
```
public final int getVersion()
```

圧縮アルゴリズムのバージョン。可能な値は次のとおりです：1. 標準圧縮、2. 高速（標準よりも高速な改良圧縮ですが、すべての画像に適用できるわけではありません）、3. 混合（高速アルゴリズムで圧縮できない画像に標準圧縮が適用されます。これにより最高の圧縮が得られますが、\"高速\" アルゴリズムよりも遅くなります。バージョン \"Fast\" は画像のリサイズには適用できません（標準の方法が使用されます）。デフォルトは \"Standard\" です。

**Returns:**
int 値です。

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定します。

**Returns:**
ブール値

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

画像を保存するために使用されるエンコーディングを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ImageEncoding 要素です。 |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

CompressImages フラグが使用されている場合の画像圧縮レベルを指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

画像の最大解像度を指定します。画像の解像度がこれより高い場合はスケーリングされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメーターより大きいときに画像がリサイズされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

圧縮アルゴリズムのバージョン。可能な値は次のとおりです：1. 標準圧縮、2. 高速（標準よりも高速な改良圧縮ですが、すべての画像に適用できるわけではありません）、3. 混合（高速アルゴリズムで圧縮できない画像に標準圧縮が適用されます。これにより最高の圧縮が得られますが、\"高速\" アルゴリズムよりも遅くなります。バージョン \"Fast\" は画像のリサイズには適用できません（標準の方法が使用されます）。デフォルトは \"Standard\" です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
