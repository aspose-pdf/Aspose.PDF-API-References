---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ドキュメント最適化アルゴリズムを記述するクラス。このクラスのインスタンスは OptimizeResources() メソッドのパラメータとして使用できます。@deprecated このクラスは廃止されました。お願いします。"
type: docs
weight: 1110
url: /ja/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

文書最適化アルゴリズムを記述するクラス。このクラスのインスタンスは OptimizeResources() メソッドのパラメータとして使用できます。@deprecated このクラスは廃止されました。代わりに com.aspose.pdf.optimization.OptimizationOptions を使用してください。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | 非推奨です。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [all](#all--) | すべてのオプションが有効化された最適化戦略を作成します。 |
| [getMaximumImageDimension](#getMaximumImageDimension--) | 最大画像寸法を指定します。既存の画像の幅または高さがこの値より大きい場合、画像サイズは比例的に縮小されます。 |
| [getResolution](#getResolution--) | CompressIamges フラグが使用されている場合の新しい画像 DPI を指定します。 |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | 最大画像寸法を指定します。既存の画像の幅または高さがこの値より大きい場合、画像サイズは比例的に縮小されます。 |
| [setResolution](#setResolution-int-) | CompressIamges フラグが使用されている場合の新しい画像 DPI を指定します。 |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

非推奨です。

### all {#all--}
```
public static Document.OptimizationOptions all()
```

すべてのオプションが有効化された最適化戦略を作成します。

**Returns:**
OptimizationOptions オブジェクトです。

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

最大画像寸法を指定します。既存の画像の幅または高さがこの値より大きい場合、画像サイズは比例的に縮小されます。

**Returns:**
画像の最大寸法

### getResolution {#getResolution--}
```
public int getResolution()
```

CompressIamges フラグが使用されている場合の新しい画像 DPI を指定します。

**Returns:**
画像解像度

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

最大画像寸法を指定します。既存の画像の幅または高さがこの値より大きい場合、画像サイズは比例的に縮小されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 寸法 |  | 画像の最大寸法 |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

CompressIamges フラグが使用されている場合の新しい画像 DPI を指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dpi |  | 画像解像度 |
