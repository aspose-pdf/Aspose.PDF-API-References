---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ドキュメント最適化アルゴリズムを記述するクラス。このクラスのインスタンスは OptimizeResources() メソッドのパラメータとして使用できます。"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

ドキュメント最適化アルゴリズムを記述するクラス。このクラスのインスタンスは OptimizeResources() メソッドのパラメータとして使用できます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [all](#all--) | すべてのオプションが有効化された最適化戦略を作成します。ドキュメントの機能を変更しないオプションのみが有効になることに注意してください。つまり、画像圧縮やフォントの埋め込み解除は有効にならず（手動で埋め込むことは可能です）。 |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | If {@link} に設定すると、すべての圧縮されていないページコンテンツストリームは {@code Document#OptimizeResources()} 実行中に FlateDecode フィルタを使用して圧縮されます。デフォルトは {@link} で、下位互換性を維持します。 |
| [getImageCompressionOptions](#getImageCompressionOptions--) | ドキュメント内の画像が圧縮されるかどうか、および圧縮のパラメータを記述するオプションのセットです。 |
| [getImageEncoding](#getImageEncoding--) | 使用される画像エンコードです。 |
| [getImageQuality](#getImageQuality--) | CompressIamges フラグが使用されている場合の画像圧縮レベルを指定します。 |
| [getMaxResoultion](#getMaxResoultion--) | 画像の最大解像度を指定します。画像の解像度がこれより高い場合は縮小されます。 |
| [isAllowReusePageContent](#isAllowReusePageContent--) | true に設定すると、ページが同一である場合にドキュメント最適化時にページコンテンツが再利用されます。 |
| [isCompressImages](#isCompressImages--) | このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定されます。 |
| [isCompressObjects](#isCompressObjects--) | このフラグが {@code } に設定されている場合、PDF オブジェクトはオブジェクトストリームにパックされ、圧縮されて PDF ファイルサイズが削減されます。 |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | このフラグが true に設定されると、リソースストリームが解析されます。重複するストリーム（つまり、ストリーム内容が同一）の場合、それらは 1 つのオブジェクトとして保存されます。これにより、同一ドキュメントが複数回連結された場合など、いくつかのケースでドキュメントサイズを削減できます。 |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | プライベート情報（ページピース情報）を削除します。 |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | このフラグが true に設定されると、すべてのドキュメントオブジェクトがチェックされ、未使用のオブジェクト（参照がないオブジェクト）はドキュメントから削除されます。 |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | このフラグが true に設定されると、すべてのリソースが使用状況でチェックされます。リソースが一度も使用されていない場合、そのリソースは削除されます。これにより、ページがドキュメントから抽出された場合など、ドキュメントサイズが削減されることがあります。 |
| [isResizeImages](#isResizeImages--) | このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメータより大きいときに画像がリサイズされます。 |
| [isSubsetFonts](#isSubsetFonts--) | true に設定すると、フォントはサブセットに変換されます。 |
| [isUnembedFonts](#isUnembedFonts--) | true に設定すると、フォントを埋め込まないようにします。 |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | true に設定すると、ページが同一である場合にドキュメント最適化時にページコンテンツが再利用されます。 |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | If {@link} に設定すると、すべての圧縮されていないページコンテンツストリームは {@code Document#OptimizeResources()} 実行中に FlateDecode フィルタを使用して圧縮されます。デフォルトは {@link} で、下位互換性を維持します。 |
| [setCompressImages](#setCompressImages-boolean-) | このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定されます。 |
| [setCompressObjects](#setCompressObjects-boolean-) | このフラグが {@code } に設定されている場合、PDF オブジェクトはオブジェクトストリームにパックされ、圧縮されて PDF ファイルサイズが削減されます。 |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | ドキュメント内の画像が圧縮されるかどうか、および圧縮のパラメータを記述するオプションのセットです。 |
| [setImageEncoding](#setImageEncoding-int-) | 使用される画像エンコードです。 |
| [setImageQuality](#setImageQuality-int-) | CompressIamges フラグが使用されている場合の画像圧縮レベルを指定します。 |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | このフラグが true に設定されると、リソースストリームが解析されます。重複するストリーム（つまり、ストリーム内容が同一）の場合、それらは 1 つのオブジェクトとして保存されます。これにより、同一ドキュメントが複数回連結された場合など、いくつかのケースでドキュメントサイズを削減できます。 |
| [setMaxResoultion](#setMaxResoultion-int-) | 画像の最大解像度を指定します。画像の解像度がこれより高い場合は縮小されます。 |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | プライベート情報（ページピース情報）を削除します。 |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | このフラグが true に設定されると、すべてのドキュメントオブジェクトがチェックされ、未使用のオブジェクト（参照がないオブジェクト）はドキュメントから削除されます。 |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | このフラグが true に設定されると、すべてのリソースが使用状況でチェックされます。リソースが一度も使用されていない場合、そのリソースは削除されます。これにより、ページがドキュメントから抽出された場合など、ドキュメントサイズが削減されることがあります。 |
| [setResizeImages](#setResizeImages-boolean-) | このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメータより大きいときに画像がリサイズされます。 |
| [setSubsetFonts](#setSubsetFonts-boolean-) | true に設定すると、フォントはサブセットに変換されます。 |
| [setUnembedFonts](#setUnembedFonts-boolean-) | true に設定すると、フォントを埋め込まないようにします。 |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

すべてのオプションが有効化された最適化戦略を作成します。ドキュメントの機能を変更しないオプションのみが有効になることに注意してください。つまり、画像圧縮やフォントの埋め込み解除は有効にならず（手動で埋め込むことは可能です）。

**Returns:**
OptimizationOptions オブジェクトです。

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

If {@link} に設定すると、すべての圧縮されていないページコンテンツストリームは {@code Document#OptimizeResources()} 実行中に FlateDecode フィルタを使用して圧縮されます。デフォルトは {@link} で、下位互換性を維持します。

**Returns:**
ブール値

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

ドキュメント内の画像が圧縮されるかどうか、および圧縮のパラメータを記述するオプションのセットです。

**Returns:**
ImageCompressionOptions インスタンスです。

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

使用される画像エンコードです。

**Returns:**
ImageEncoding 要素です。

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

CompressIamges フラグが使用されている場合の画像圧縮レベルを指定します。

**Returns:**
int 値 @deprecated 代わりに ImageCompressionOptions.ImageQuality を使用してください。

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

画像の最大解像度を指定します。画像の解像度がこれより高い場合は縮小されます。

**Returns:**
int 値です。

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

true に設定すると、ページが同一である場合にドキュメント最適化時にページコンテンツが再利用されます。

**Returns:**
ブール値

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定されます。

**Returns:**
boolean 値 @deprecated 代わりに ImageCompressionOptions.CompressImages を使用してください。

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

このフラグが {@code } に設定されている場合、PDF オブジェクトはオブジェクトストリームにパックされ、圧縮されて PDF ファイルサイズが削減されます。

**Returns:**
ブール値

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

このフラグが true に設定されると、リソースストリームが解析されます。重複するストリーム（つまり、ストリーム内容が同一）の場合、それらは 1 つのオブジェクトとして保存されます。これにより、同一ドキュメントが複数回連結された場合など、いくつかのケースでドキュメントサイズを削減できます。

**Returns:**
ブール値

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

プライベート情報（ページピース情報）を削除します。

**Returns:**
ブール値

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

このフラグが true に設定されると、すべてのドキュメントオブジェクトがチェックされ、未使用のオブジェクト（参照がないオブジェクト）はドキュメントから削除されます。

**Returns:**
ブール値

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

このフラグが true に設定されると、すべてのリソースが使用状況でチェックされます。リソースが一度も使用されていない場合、そのリソースは削除されます。これにより、ページがドキュメントから抽出された場合など、ドキュメントサイズが削減されることがあります。

**Returns:**
ブール値

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメータより大きいときに画像がリサイズされます。

**Returns:**
boolean 値 @deprecated 代わりに ImageCompressionOptions.ResizeImages を使用してください。

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

true に設定すると、フォントはサブセットに変換されます。

**Returns:**
ブール値

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

true に設定すると、フォントを埋め込まないようにします。

**Returns:**
ブール値

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

true に設定すると、ページが同一である場合にドキュメント最適化時にページコンテンツが再利用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

If {@link} に設定すると、すべての圧縮されていないページコンテンツストリームは {@code Document#OptimizeResources()} 実行中に FlateDecode フィルタを使用して圧縮されます。デフォルトは {@link} で、下位互換性を維持します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

このフラグが true に設定されている場合、ドキュメント内の画像が圧縮されます。圧縮レベルは ImageQuality プロパティで指定されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | boolean 値 @deprecated 代わりに ImageCompressionOptions.CompressImages を使用してください。 |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

このフラグが {@code } に設定されている場合、PDF オブジェクトはオブジェクトストリームにパックされ、圧縮されて PDF ファイルサイズが削減されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
ドキュメント内の画像が圧縮されるかどうか、および圧縮のパラメータを記述するオプションのセットです。

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

使用される画像エンコードです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ImageEncoding 要素です。 |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

CompressIamges フラグが使用されている場合の画像圧縮レベルを指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値 @deprecated 代わりに ImageCompressionOptions.ImageQuality を使用してください。 |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

このフラグが true に設定されると、リソースストリームが解析されます。重複するストリーム（つまり、ストリーム内容が同一）の場合、それらは 1 つのオブジェクトとして保存されます。これにより、同一ドキュメントが複数回連結された場合など、いくつかのケースでドキュメントサイズを削減できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

画像の最大解像度を指定します。画像の解像度がこれより高い場合は縮小されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

プライベート情報（ページピース情報）を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

このフラグが true に設定されると、すべてのドキュメントオブジェクトがチェックされ、未使用のオブジェクト（参照がないオブジェクト）はドキュメントから削除されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

このフラグが true に設定されると、すべてのリソースが使用状況でチェックされます。リソースが一度も使用されていない場合、そのリソースは削除されます。これにより、ページがドキュメントから抽出された場合など、ドキュメントサイズが削減されることがあります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

このフラグが true に設定され、かつ CompressImages が true の場合、画像の解像度が指定された MaxResolution パラメータより大きいときに画像がリサイズされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | boolean 値 @deprecated 代わりに ImageCompressionOptions.ResizeImages を使用してください。 |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

true に設定すると、フォントはサブセットに変換されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

true に設定すると、フォントを埋め込まないようにします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
