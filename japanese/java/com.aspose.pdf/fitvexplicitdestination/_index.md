---
title: "FitVExplicitDestination"
linktitle: "FitVExplicitDestination"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ウィンドウの左端に左座標が配置され、ページの内容がちょうど拡大表示される明示的なデスティネーションを表します。"
type: docs
weight: 1580
url: /ja/java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitVExplicitDestination extends ExplicitDestination
```

ページの水平座標 left がウィンドウの左端に位置し、ページの内容がページ全体の高さがウィンドウ内に収まるように拡大された、明示的な表示先を表します。left が null の場合は、そのパラメータの現在値を変更せずに保持することを意味します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Document-int-double-) | リモートの明示的なデスティネーションを作成します。 |
| [FitVExplicitDestination](#FitVExplicitDestination-int-double-) | リモートの明示的なデスティネーションを作成します。 |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | インスタンスを作成し、DOM ページオブジェクトと left パラメータで初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLeft](#getLeft--) | ウィンドウの左端に配置された水平座標 left を取得します。 |
| [toString](#toString--) | オブジェクトの状態を文字列値に変換します。例: "1 FitV 100"。 |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Document-int-double-}
リモートの明示的なデスティネーションを作成します。

### FitVExplicitDestination {#FitVExplicitDestination-int-double-}
```
public FitVExplicitDestination(int pageNumber, double left)
```

リモートの明示的なデスティネーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | リモートドキュメントのデスティネーションページ番号です。 |
| left |  | ウィンドウの左端に配置された水平座標 left。 |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
インスタンスを作成し、DOM ページオブジェクトと left パラメータで初期化します。

### getLeft {#getLeft--}
```
public double getLeft()
```

ウィンドウの左端に配置された水平座標 left を取得します。

**Returns:**
double 値

### toString {#toString--}
```
public String toString()
```

オブジェクトの状態を文字列値に変換します。例: "1 FitV 100"。

**Returns:**
オブジェクトの状態を表す文字列値です。
