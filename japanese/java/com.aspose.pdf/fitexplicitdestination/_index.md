---
title: "FitExplicitDestination"
linktitle: "FitExplicitDestination"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ全体がウィンドウ内に水平・垂直に収まるように、内容をちょうど拡大表示する明示的なデスティネーションを表します。もし..."
type: docs
weight: 1550
url: /ja/java/com.aspose.pdf/fitexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitExplicitDestination extends ExplicitDestination
```

ページ全体がウィンドウ内に水平・垂直の両方向で収まるように内容が拡大された、明示的な表示先を表します。必要な水平および垂直の拡大率が異なる場合は、両者のうち小さい方を使用し、もう一方の方向でページをウィンドウの中央に配置します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Document-int-) | リモートの明示的なデスティネーションを作成します。 |
| [FitExplicitDestination](#FitExplicitDestination-int-) | リモートの明示的なデスティネーションを作成します。 |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Page-) | ローカルの明示的なデスティネーションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [toString](#toString--) | オブジェクトの状態を文字列値に変換します。例: "1 Fit"。 |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Document-int-}
リモートの明示的なデスティネーションを作成します。

### FitExplicitDestination {#FitExplicitDestination-int-}
```
public FitExplicitDestination(int pageNumber)
```

リモートの明示的なデスティネーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | リモートドキュメントのデスティネーションページ番号です。 |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Page-}
ローカルの明示的なデスティネーションを作成します。

### toString {#toString--}
```
public String toString()
```

オブジェクトの状態を文字列値に変換します。例: "1 Fit"。

**Returns:**
オブジェクトの状態を表す文字列値です。
