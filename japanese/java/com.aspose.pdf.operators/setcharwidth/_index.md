---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "d0 演算子を表すクラス（グリフ幅を設定）。"
type: docs
weight: 510
url: /ja/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

d0 演算子を表すクラス（グリフ幅を設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | コンストラクタ。 |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getWx](#getWx--) | グリフ座標の水平方向の変位。 |
| [getWy](#getWy--) | グリフ座標の垂直方向の変位。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

コンストラクタ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| wx |  | グリフの水平変位。 |
| wy |  | グリフの垂直変位。 |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getWx {#getWx--}
```
public double getWx()
```

グリフ座標の水平方向の変位。

**Returns:**
double 値

### getWy {#getWy--}
```
public double getWy()
```

グリフ座標の垂直方向の変位。

**Returns:**
double 値

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

演算子のテキスト表現を返します。

**Returns:**
表現のテキスト表現
