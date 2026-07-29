---
title: "IconFit"
linktitle: "IconFit"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ウィジェット注釈のアイコンが注釈矩形内でどのように表示されるかを説明します"
type: docs
weight: 2210
url: /ja/java/com.aspose.pdf/iconfit/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.IconFit

```
public final class IconFit extends Object
```

ウィジェット注釈のアイコンが注釈矩形内でどのように表示されるかを説明します

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLeftoverBottom](#getLeftoverBottom--) | アイコンの下部に割り当てるスペースを取得します。 |
| [getLeftoverLeft](#getLeftoverLeft--) | アイコンの左側に割り当てるスペースを取得します。 |
| [getScalingMode](#getScalingMode--) | 使用すべきスケーリングのタイプ。 |
| [getScalingReason](#getScalingReason--) | スケーリング理由を取得します。 |
| [isSpreadOnBorder](#isSpreadOnBorder--) | true の場合、ボタンの外観が注釈の境界内に完全に収まるようにスケーリングされ、境界線の幅は考慮されません。 |
| [nameToScalingMode](#nameToScalingMode-java.lang.String-) | スケーリングモード名を ScalingMode オブジェクトに変換します。 |
| [nameToScalingReason](#nameToScalingReason-java.lang.String-) | スケーリング理由の名前を ScalingReason オブジェクトに変換します。 |
| [scalingModeToName](#scalingModeToName-int-) | スケーリングモードオブジェクトを名前に変換します。 |
| [scalingReasonToName](#scalingReasonToName-int-) | スケーリング理由オブジェクトを名前に変換します。 |
| [setLeftoverBottom](#setLeftoverBottom-double-) | アイコンの下部に割り当てるスペースを設定します。 |
| [setLeftoverLeft](#setLeftoverLeft-double-) | アイコンの左側に割り当てるスペースを設定します。 |
| [setScalingMode](#setScalingMode-int-) | 使用すべきスケーリングのタイプ。 |
| [setScalingReason](#setScalingReason-int-) | スケーリング理由を設定します。 |
| [setSpreadOnBorder](#setSpreadOnBorder-boolean-) | true の場合、ボタンの外観が注釈の境界内に完全に収まるようにスケーリングされ、境界線の幅は考慮されません。 |

### getLeftoverBottom {#getLeftoverBottom--}
```
public double getLeftoverBottom()
```

アイコンの下部に割り当てるスペースを取得します。

**Returns:**
下部に割り当てるスペース

### getLeftoverLeft {#getLeftoverLeft--}
```
public double getLeftoverLeft()
```

アイコンの左側に割り当てるスペースを取得します。

**Returns:**
アイコンの左側に割り当てるスペース。

### getScalingMode {#getScalingMode--}
```
public int getScalingMode()
```

使用すべきスケーリングのタイプ。

**Returns:**
ScalingMode の値 @see ScalingMode

### getScalingReason {#getScalingReason--}
```
public int getScalingReason()
```

スケーリング理由を取得します。

**Returns:**
ScalingReason の値 @see ScalingReason

### isSpreadOnBorder {#isSpreadOnBorder--}
```
public boolean isSpreadOnBorder()
```

true の場合、ボタンの外観が注釈の境界内に完全に収まるようにスケーリングされ、境界線の幅は考慮されません。

**Returns:**
ブール値

### nameToScalingMode {#nameToScalingMode-java.lang.String-}
スケーリングモード名を ScalingMode オブジェクトに変換します。

### nameToScalingReason {#nameToScalingReason-java.lang.String-}
スケーリング理由の名前を ScalingReason オブジェクトに変換します。

### scalingModeToName {#scalingModeToName-int-}
```
public static String scalingModeToName(int mode)
```

スケーリングモードオブジェクトを名前に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| モード |  | スケーリングモードオブジェクト。 |

**Returns:**
スケーリングモード名。

### scalingReasonToName {#scalingReasonToName-int-}
```
public static String scalingReasonToName(int reason)
```

スケーリング理由オブジェクトを名前に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 理由 |  | 変換されるスケーリング理由オブジェクト。 |

**Returns:**
スケーリング理由の名前。

### setLeftoverBottom {#setLeftoverBottom-double-}
```
public void setLeftoverBottom(double value)
```

アイコンの下部に割り当てるスペースを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 下部に割り当てるスペース |

### setLeftoverLeft {#setLeftoverLeft-double-}
```
public void setLeftoverLeft(double value)
```

アイコンの左側に割り当てるスペースを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | アイコンの左側に割り当てるスペース。 |

### setScalingMode {#setScalingMode-int-}
```
public void setScalingMode(int value)
```

使用すべきスケーリングのタイプ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ScalingMode の値 @see ScalingMode |

### setScalingReason {#setScalingReason-int-}
```
public void setScalingReason(int value)
```

スケーリング理由を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ScalingReason の値 @see ScalingReason |

### setSpreadOnBorder {#setSpreadOnBorder-boolean-}
```
public void setSpreadOnBorder(boolean value)
```

true の場合、ボタンの外観が注釈の境界内に完全に収まるようにスケーリングされ、境界線の幅は考慮されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
