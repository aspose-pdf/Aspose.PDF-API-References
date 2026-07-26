---
title: "SetLineWidth"
linktitle: "SetLineWidth"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "w 演算子を表すクラス（線幅を設定）。"
type: docs
weight: 690
url: /ja/java/com.aspose.pdf.operators/setlinewidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineWidth

```
public class SetLineWidth extends Operator
```

w 演算子を表すクラス（線幅を設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetLineWidth](#SetLineWidth-double-) | 幅の値で演算子を初期化します。 |
| [SetLineWidth](#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getWidth](#getWidth--) | 線の幅を取得します。 |
| [setWidth](#setWidth-double-) | 線の幅を設定します。 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### SetLineWidth {#SetLineWidth-double-}
```
public SetLineWidth(double width)
```

幅の値で演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 幅の値。 |

### SetLineWidth {#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getWidth {#getWidth--}
```
public double getWidth()
```

線の幅を取得します。

**Returns:**
線の幅。

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

線の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 線の幅。 |

### toString {#toString--}
```
public String toString()
```

演算子のテキスト表現を返します。

**Returns:**
演算子のテキスト表現。
