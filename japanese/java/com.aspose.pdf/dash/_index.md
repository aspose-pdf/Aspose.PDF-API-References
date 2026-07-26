---
title: "Dash"
linktitle: "Dash"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "線の破線パターンを表すクラスです。"
type: docs
weight: 910
url: /ja/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

線の破線パターンを表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Dash](#Dash-int:A-) | Dash のコンストラクタです。破線の境界線を描画する際に使用される、破線と隙間のパターンを定義します。 |
| [Dash](#Dash-int-int-) | Dash のコンストラクタです。指定された破線と隙間で破線の境界線を定義し、境界線全体で変更されません。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOff](#getOff--) | 破線間の最初の隙間の長さを取得または設定します。 |
| [getOn](#getOn--) | 最初の破線の長さを取得または設定します。 |
| [getPattern](#getPattern--) | 破線の境界線を描画する際に使用される、破線と隙間のパターンを定義する dash 配列を取得します。 |
| [setOff](#setOff-int-) | 破線間の最初の隙間の長さを取得または設定します。 |
| [setOn](#setOn-int-) | 最初の破線の長さを取得または設定します。 |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Dash のコンストラクタです。破線の境界線を描画する際に使用される、破線と隙間のパターンを定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| パターン |  | 破線と隙間のパターンを定義する dash 配列（最低2つの値）です。 |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Dash のコンストラクタです。指定された破線と隙間で破線の境界線を定義し、境界線全体で変更されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| オン |  | 破線の長さです。 |
| オフ |  | 隙間の長さです。 |

### getOff {#getOff--}
```
public final int getOff()
```

破線間の最初の隙間の長さを取得または設定します。

**Returns:**
int 値です。

### getOn {#getOn--}
```
public final int getOn()
```

最初の破線の長さを取得または設定します。

**Returns:**
int 値です。

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

破線の境界線を描画する際に使用される、破線と隙間のパターンを定義する dash 配列を取得します。

**Returns:**
int 配列

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

破線間の最初の隙間の長さを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

最初の破線の長さを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
