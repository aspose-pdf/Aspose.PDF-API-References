---
title: "FitHExplicitDestination"
linktitle: "FitHExplicitDestination"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ウィンドウの上端に垂直座標 top が配置され、ページの内容がちょうど拡大表示される明示的なデスティネーションを表します。"
type: docs
weight: 1560
url: /ja/java/com.aspose.pdf/fithexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitHExplicitDestination extends ExplicitDestination
```

ページの垂直座標 top がウィンドウの上端に位置し、ページの内容がページ全体の幅がウィンドウ内に収まるように拡大された、明示的な表示先を表します。top が null の場合は、そのパラメータの現在値を変更せずに保持することを意味します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Document-int-double-) | リモートの明示的なデスティネーションを作成します。 |
| [FitHExplicitDestination](#FitHExplicitDestination-int-double-) | リモートの明示的なデスティネーションを作成します。 |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Page-double-) | インスタンスを作成し、DOM ページオブジェクトと top パラメータで初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTop](#getTop--) | ウィンドウの上端に配置された垂直座標 top を取得します。 |
| [toString](#toString--) | オブジェクトの状態を文字列値に変換します。例: "1 FitH 100"。 |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Document-int-double-}
リモートの明示的なデスティネーションを作成します。

### FitHExplicitDestination {#FitHExplicitDestination-int-double-}
```
public FitHExplicitDestination(int pageNumber, double top)
```

リモートの明示的なデスティネーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | リモートドキュメントのデスティネーションページ番号です。 |
| 上部 |  | ウィンドウの上端に配置された垂直座標 top。 |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Page-double-}
インスタンスを作成し、DOM ページオブジェクトと top パラメータで初期化します。

### getTop {#getTop--}
```
public double getTop()
```

ウィンドウの上端に配置された垂直座標 top を取得します。

**Returns:**
double 値

### toString {#toString--}
```
public String toString()
```

オブジェクトの状態を文字列値に変換します。例: "1 FitH 100"。

**Returns:**
オブジェクトの状態を表す文字列値です。
