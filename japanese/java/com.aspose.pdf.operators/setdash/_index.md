---
title: "SetDash"
linktitle: "SetDash"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "d 演算子を表すクラス（線の破線パターンを設定）。"
type: docs
weight: 610
url: /ja/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

d 演算子を表すクラス（線の破線パターンを設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | ダッシュパターン設定演算子を作成します。 |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getPattern](#getPattern--) | ダッシュパターン。配列の要素は、交互のダッシュとギャップの長さを指定する数値でなければなりません。要素が1つの配列の場合、ダッシュとギャップの長さは等しくなります。 |
| [getPhase](#getPhase--) | ダッシュフェーズ。パスのストロークを開始する前に、ダッシュ配列は循環され、ダッシュとギャップの長さが加算されます。累積長さがダッシュフェーズで指定された値に等しくなると、パスのストロークが開始され、以降はダッシュ配列が循環的に使用されます。 |
| [setPattern](#setPattern-int:A-) | ダッシュパターン。配列の要素は、交互のダッシュとギャップの長さを指定する数値でなければなりません。要素が1つの配列の場合、ダッシュとギャップの長さは等しくなります。 |
| [setPhase](#setPhase-int-) | ダッシュフェーズ。パスのストロークを開始する前に、ダッシュ配列は循環され、ダッシュとギャップの長さが加算されます。累積長さがダッシュフェーズで指定された値に等しくなると、パスのストロークが開始され、以降はダッシュ配列が循環的に使用されます。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |
| [toString](#toString--) | 演算子の文字列表現を取得します。 |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

ダッシュパターン設定演算子を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| パターン |  | ダッシュパターンを定義する配列。 |
| フェーズ |  | ダッシュフェーズ。 |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getPattern {#getPattern--}
```
public int[] getPattern()
```

ダッシュパターン。配列の要素は、交互のダッシュとギャップの長さを指定する数値でなければなりません。要素が1つの配列の場合、ダッシュとギャップの長さは等しくなります。

**Returns:**
int 配列

### getPhase {#getPhase--}
```
public int getPhase()
```

ダッシュフェーズ。パスのストロークを開始する前に、ダッシュ配列は循環され、ダッシュとギャップの長さが加算されます。累積長さがダッシュフェーズで指定された値に等しくなると、パスのストロークが開始され、以降はダッシュ配列が循環的に使用されます。

**Returns:**
int 値です。

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

ダッシュパターン。配列の要素は、交互のダッシュとギャップの長さを指定する数値でなければなりません。要素が1つの配列の場合、ダッシュとギャップの長さは等しくなります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 配列 |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

ダッシュフェーズ。パスのストロークを開始する前に、ダッシュ配列は循環され、ダッシュとギャップの長さが加算されます。累積長さがダッシュフェーズで指定された値に等しくなると、パスのストロークが開始され、以降はダッシュ配列が循環的に使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

内部使用のみ！

**Returns:**
ICommand 値 ICommand オブジェクト

### toString {#toString--}
```
public String toString()
```

演算子の文字列表現を取得します。

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
