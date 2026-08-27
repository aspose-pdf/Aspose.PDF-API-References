---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "d1 演算子を表すクラス（グリフとバウンディングボックスを設定）。"
type: docs
weight: 520
url: /ja/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

d1 演算子を表すクラス（グリフとバウンディングボックスを設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | SetCharWidthBoundingBox 演算子を初期化します。 |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getLlx](#getLlx--) | バウンディング矩形の左下水平座標。 |
| [getLly](#getLly--) | バウンディング矩形の左下垂直座標。 |
| [getUrx](#getUrx--) | バウンディング矩形の右上水平座標。 |
| [getUry](#getUry--) | バウンディング矩形の右上垂直座標。 |
| [getWx](#getWx--) | グリフの水平変位。 |
| [getWy](#getWy--) | グリフの垂直変位。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

SetCharWidthBoundingBox 演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| wx |  | グリフ座標系における水平変位を示します。 |
| wy |  | グリフ座標系における垂直変位を示します。0 である必要があります。 |
| llx |  | 左下隅の X 座標を示します。 |
| lly |  | 左下隅の Y 座標を示します。 |
| urx |  | 右上隅の X 座標を示します。 |
| ury |  | 右上隅の Y 座標を示します。 |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getLlx {#getLlx--}
```
public double getLlx()
```

バウンディング矩形の左下水平座標。

**Returns:**
double 値

### getLly {#getLly--}
```
public double getLly()
```

バウンディング矩形の左下垂直座標。

**Returns:**
double 値

### getUrx {#getUrx--}
```
public double getUrx()
```

バウンディング矩形の右上水平座標。

**Returns:**
double 値

### getUry {#getUry--}
```
public double getUry()
```

バウンディング矩形の右上垂直座標。

**Returns:**
double 値

### getWx {#getWx--}
```
public double getWx()
```

グリフの水平変位。

**Returns:**
double 値

### getWy {#getWy--}
```
public double getWy()
```

グリフの垂直変位。

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
