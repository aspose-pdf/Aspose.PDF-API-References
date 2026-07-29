---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "MemoryExtender クラスを表します。ヒープメモリが制限されたシステムで大きなファイルを使用する場合、ディスク領域を一時的なスワップメモリとして使用できるように有効にできます。"
type: docs
weight: 3020
url: /ja/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

MemoryExtender クラスを表します。ヒープメモリが制限されたシステムで大きなファイルを使用する場合、ディスク領域を一時的なスワップメモリとして使用できるように有効にできます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | カスタムキャッシュアナライザーを取得します。 |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | ページから画像への変換で使用される単一要素のレンダリングの最大時間です。デフォルト値は10000ミリ秒です。isSkipHeavyContentEnabled() == true の場合にのみ使用されます。 |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | EnabledMultiPageImageCache フィールドのステータスを取得します。 |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | OptimizedMemoryStream をデフォルトのメモリストレージとして使用するかどうかが有効です。2 GB を超える大きなドキュメントの処理に必要です。デフォルト値は FALSE です。 |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | OptimizedMemoryStream をデフォルトのメモリストレージとして使用するかどうかが有効です。2 GB を超える大きなドキュメントの処理に必要です。デフォルト値は FALSE です。 |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | ヒープメモリが不足している状態でのレンダリング時に、メモリ消費が大きいオブジェクトをスキップするかどうかが有効です。デフォルト値は FALSE です。 |
| [isSwapEnabled](#isSwapEnabled--) | ディスク領域を一時的なスワップメモリとして使用するかどうかが有効です。デフォルト値は FALSE です。 |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | 欠落しているフォルダーを自動的に作成すべきかどうかを示す値を取得します。<p>{@code true} に設定すると、パスで保存する Aspose メソッドは、対象フォルダー構造が存在しない場合に作成しようとします。<p>デフォルト値は {@code false} です。 |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | 新しいカスタムキャッシュアナライザーを適用します。 |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | ページから画像への変換で使用される単一要素のレンダリングの最大時間です。デフォルト値は10000ミリ秒です。isSkipHeavyContentEnabled() == true の場合にのみ使用されます。 |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | EnabledMultiPageImageCache フィールドの新しいステータスを設定します。 |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | ヒープメモリが不足している状態でのレンダリング時に、メモリ消費が大きいオブジェクトをスキップするフラグを有効に設定します。 |
| [setSwapEnabled](#setSwapEnabled-boolean-) | ディスク領域を一時的なスワップメモリとして使用するかどうかのフラグを設定します。 |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | 欠落しているフォルダーを自動的に作成すべきかどうかを示す値を設定します。<p>{@code true} に設定すると、パスで保存する Aspose メソッドは、対象フォルダー構造が存在しない場合に作成しようとします。<p>デフォルト値は {@code false} です。 |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

カスタムキャッシュアナライザーを取得します。

**Returns:**
CallBackPageImage オブジェクト

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

ページから画像への変換で使用される単一要素のレンダリングの最大時間です。デフォルト値は10000ミリ秒です。isSkipHeavyContentEnabled() == true の場合にのみ使用されます。

**Returns:**
int 値 ミリ秒数

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

EnabledMultiPageImageCache フィールドのステータスを取得します。

**Returns:**
ブール値

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

OptimizedMemoryStream をデフォルトのメモリストレージとして使用するかどうかが有効です。2 GB を超える大きなドキュメントの処理に必要です。デフォルト値は FALSE です。

**Returns:**
ブール値

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

OptimizedMemoryStream をデフォルトのメモリストレージとして使用するかどうかが有効です。2 GB を超える大きなドキュメントの処理に必要です。デフォルト値は FALSE です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

ヒープメモリが不足している状態でのレンダリング時に、メモリ消費が大きいオブジェクトをスキップするかどうかが有効です。デフォルト値は FALSE です。

**Returns:**
ブール値

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

ディスク領域を一時的なスワップメモリとして使用するかどうかが有効です。デフォルト値は FALSE です。

**Returns:**
ブール値

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

欠落しているフォルダーを自動的に作成すべきかどうかを示す値を取得します。<p>{@code true} に設定すると、パスで保存する Aspose メソッドは、対象フォルダー構造が存在しない場合に作成しようとします。<p>デフォルト値は {@code false} です。

**Returns:**
ブール値

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
新しいカスタムキャッシュアナライザーを適用します。

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

ページから画像への変換で使用される単一要素のレンダリングの最大時間です。デフォルト値は10000ミリ秒です。isSkipHeavyContentEnabled() == true の場合にのみ使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値 ミリ秒数 |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

EnabledMultiPageImageCache フィールドの新しいステータスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | ブール値 |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

ヒープメモリが不足している状態でのレンダリング時に、メモリ消費が大きいオブジェクトをスキップするフラグを有効に設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

ディスク領域を一時的なスワップメモリとして使用するかどうかのフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

欠落しているフォルダーを自動的に作成すべきかどうかを示す値を設定します。<p>{@code true} に設定すると、パスで保存する Aspose メソッドは、対象フォルダー構造が存在しない場合に作成しようとします。<p>デフォルト値は {@code false} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
