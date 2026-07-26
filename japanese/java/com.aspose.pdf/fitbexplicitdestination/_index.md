---
title: "FitBExplicitDestination"
linktitle: "FitBExplicitDestination"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページの内容がウィンドウ内に水平・垂直に完全に収まるように拡大表示する、明示的な宛先を表します。"
type: docs
weight: 1520
url: /ja/java/com.aspose.pdf/fitbexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBExplicitDestination extends ExplicitDestination
```

ページの内容が水平・垂直の両方向でウィンドウ内にバウンディングボックス全体が収まるように拡大された、明示的な表示先を表します。必要な水平および垂直の拡大率が異なる場合は、両者のうち小さい方を使用し、もう一方の方向でバウンディングボックスをウィンドウの中央に配置します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Document-int-) | リモートの明示的なデスティネーションを作成します。 |
| [FitBExplicitDestination](#FitBExplicitDestination-int-) | リモートの明示的なデスティネーションを作成します。 |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Page-) | インスタンスを作成し、DOM ページオブジェクトで初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [toString](#toString--) | オブジェクトの状態を文字列値に変換します。例: "1 FitB"。 |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Document-int-}
リモートの明示的なデスティネーションを作成します。

### FitBExplicitDestination {#FitBExplicitDestination-int-}
```
public FitBExplicitDestination(int pageNumber)
```

リモートの明示的なデスティネーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | リモートドキュメントのデスティネーションページ番号です。 |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Page-}
インスタンスを作成し、DOM ページオブジェクトで初期化します。

### toString {#toString--}
```
public String toString()
```

オブジェクトの状態を文字列値に変換します。例: "1 FitB"。

**Returns:**
オブジェクトの状態を表す文字列値です。
