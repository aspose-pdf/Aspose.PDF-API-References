---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "左、下、右、上の座標で指定された矩形にちょうど収まるように、ページ内容を拡大表示する明示的なデスティネーションを表します。"
type: docs
weight: 1570
url: /ja/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

ページの内容が left、bottom、right、top の座標で指定された矩形がウィンドウ内に水平・垂直の両方向で完全に収まるように拡大された、明示的な表示先を表します。必要な水平および垂直の拡大率が異なる場合は、両者のうち小さい方を使用し、もう一方の方向で矩形をウィンドウの中央に配置します。任意のパラメータが null の場合、予測できない動作になる可能性があります。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | リモートの明示的なデスティネーションを作成します。 |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | リモートの明示的なデスティネーションを作成します。 |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | インスタンスを作成し、DOM ページオブジェクトと可視パラメータで初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBottom](#getBottom--) | 表示矩形の下側垂直座標を取得します。 |
| [getLeft](#getLeft--) | 表示矩形の左側水平座標を取得します。 |
| [getRight](#getRight--) | 表示矩形の右側水平座標を取得します。 |
| [getTop](#getTop--) | 表示矩形の上側垂直座標を取得します。 |
| [toString](#toString--) | オブジェクトの状態を文字列値に変換します。例: "1 FitR 100 200 300 400"。 |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
リモートの明示的なデスティネーションを作成します。

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

リモートの明示的なデスティネーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | リモートドキュメントのデスティネーションページ番号です。 |
| left |  | 表示矩形の左側水平座標。 |
| bottom |  | 表示矩形の下側垂直座標。 |
| 右 |  | 表示矩形の右側水平座標。 |
| 上部 |  | 表示矩形の上側垂直座標。 |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
インスタンスを作成し、DOM ページオブジェクトと可視パラメータで初期化します。

### getBottom {#getBottom--}
```
public double getBottom()
```

表示矩形の下側垂直座標を取得します。

**Returns:**
double 値

### getLeft {#getLeft--}
```
public double getLeft()
```

表示矩形の左側水平座標を取得します。

**Returns:**
double 値

### getRight {#getRight--}
```
public double getRight()
```

表示矩形の右側水平座標を取得します。

**Returns:**
double 値

### getTop {#getTop--}
```
public double getTop()
```

表示矩形の上側垂直座標を取得します。

**Returns:**
double 値

### toString {#toString--}
```
public String toString()
```

オブジェクトの状態を文字列値に変換します。例: "1 FitR 100 200 300 400"。

**Returns:**
オブジェクトの状態を表す文字列値です。
