---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスはグラフィック要素の境界を表します。"
type: docs
weight: 370
url: /ja/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

このクラスはグラフィック要素の境界を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BorderInfo](#BorderInfo--) | 新しい {@code BorderInfo} クラスのインスタンスを初期化します。 |
| [BorderInfo](#BorderInfo-int-) | 新しい {@code BorderInfo} クラスのインスタンスを初期化します。 |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | 新しい {@code BorderInfo} クラスのインスタンスを初期化します。 |
| [BorderInfo](#BorderInfo-int-float-) | 新しい {@code BorderInfo} クラスのインスタンスを初期化します。 |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | 新しい {@code BorderInfo} クラスのインスタンスを初期化します。 |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | 新しい {@code BorderInfo} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | 新しい BorderInfo オブジェクトをクローンします。 |
| [getBottom](#getBottom--) | 境界線の下部を示すオブジェクトを取得します。 |
| [getLeft](#getLeft--) | ボーダーの左側を示す {@code GraphInfo} オブジェクトを取得します。 |
| [getRight](#getRight--) | ボーダーの右側を示す {@code GraphInfo} オブジェクトを取得します。 |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | 丸みを帯びたボーダー半径を取得します。 |
| [getTop](#getTop--) | 上部のボーダーを示す {@code GraphInfo} オブジェクトを取得します。 |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | ボーダーの下部を示すオブジェクトを設定します。 |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | ボーダーの左側を示す {@code GraphInfo} オブジェクトを設定します。 |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | ボーダーの右側を示す {@code GraphInfo} オブジェクトを設定します。 |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | 丸みを帯びたボーダー半径を設定します。 |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | ボーダーの上部を示す {@code GraphInfo} オブジェクトを設定します。 |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

新しい {@code BorderInfo} クラスのインスタンスを初期化します。

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

新しい {@code BorderInfo} クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| borderSide |  | ボーダーサイド情報を示します。例: (BorderSide.Left \ | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
新しい {@code BorderInfo} クラスのインスタンスを初期化します。

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

新しい {@code BorderInfo} クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| borderSide |  | ボーダーサイド情報を示します。例: (BorderSide.Left \ | BorderSide.Top). |
| borderWidth |  | ボーダーの幅です。 |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
新しい {@code BorderInfo} クラスのインスタンスを初期化します。

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
新しい {@code BorderInfo} クラスのインスタンスを初期化します。

### deepClone {#deepClone--}
```
public Object deepClone()
```

新しい BorderInfo オブジェクトをクローンします。

**Returns:**
新しい BorderInfo オブジェクトです。

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

境界線の下部を示すオブジェクトを取得します。

**Returns:**
bottom

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

ボーダーの左側を示す {@code GraphInfo} オブジェクトを取得します。

**Returns:**
ボーダーの左側を示すオブジェクト。

### getRight {#getRight--}
```
public GraphInfo getRight()
```

ボーダーの右側を示す {@code GraphInfo} オブジェクトを取得します。

**Returns:**
ボーダーの右側を示すオブジェクト。

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

丸みを帯びたボーダー半径を取得します。

**Returns:**
値

### getTop {#getTop--}
```
public GraphInfo getTop()
```

上部のボーダーを示す {@code GraphInfo} オブジェクトを取得します。

**Returns:**
上部のボーダーを示すオブジェクト

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
ボーダーの下部を示すオブジェクトを設定します。

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
ボーダーの左側を示す {@code GraphInfo} オブジェクトを設定します。

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
ボーダーの右側を示す {@code GraphInfo} オブジェクトを設定します。

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

丸みを帯びたボーダー半径を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
ボーダーの上部を示す {@code GraphInfo} オブジェクトを設定します。
