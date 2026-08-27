---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "余白またはコンテンツサイズの値をデフォルトの空間単位のパーセンテージで指定します。このクラスは ContentsResizeParameters で使用されます。"
type: docs
weight: 310
url: /ja/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

余白またはコンテンツサイズの値をデフォルトの空間単位のパーセンテージで指定します。このクラスは ContentsResizeParameters で使用されます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [auto](#auto--) | 自動計算された値を初期化します。 |
| [getValue](#getValue--) | 指定された値を取得します。単位を取得するには Unit プロパティを使用します。 |
| [isPercent](#isPercent--) | 値がパーセントで表されている場合は true、デフォルト単位で表されている場合は false を取得します。 |
| [percents](#percents-double-) | 値をパーセントで初期化します。 |
| [setPercentValue](#setPercentValue-double-) | ページサイズのパーセントで値を設定します。 |
| [setUnitValue](#setUnitValue-double-) | デフォルトの空間単位で値を設定します。 |
| [units](#units-double-) | デフォルトの空間単位で値を初期化します。 |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

自動計算された値を初期化します。

**Returns:**
新しい値のインスタンスです。

### getValue {#getValue--}
```
public final double getValue()
```

指定された値を取得します。単位を取得するには Unit プロパティを使用します。

**Returns:**
double 値

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

値がパーセントで表されている場合は true、デフォルト単位で表されている場合は false を取得します。

**Returns:**
ブール値

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

値をパーセントで初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | パーセントでの値です。 |

**Returns:**
新しい値のインスタンスです。

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

ページサイズのパーセントで値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

デフォルトの空間単位で値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

デフォルトの空間単位で値を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 単位での値です。 |

**Returns:**
新しい値のインスタンスです。
