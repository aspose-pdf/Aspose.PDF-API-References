---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "TL 演算子を表すクラス（テキストリーディングを設定）。"
type: docs
weight: 740
url: /ja/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

TL 演算子を表すクラス（テキストリーディングを設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | テキストリーディング演算子のコンストラクタです。 |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getLeading](#getLeading--) | テキストのリーディングを取得します。 |
| [setLeading](#setLeading-double-) | テキストのリーディングを設定します。 |
| [toString](#toString--) | 演算子のテキストコードを生成します。 |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

テキストリーディング演算子のコンストラクタです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| leading |  | テキストのリーディング。 |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getLeading {#getLeading--}
```
public double getLeading()
```

テキストのリーディングを取得します。

**Returns:**
double 値

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

テキストのリーディングを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### toString {#toString--}
```
public String toString()
```

演算子のテキストコードを生成します。

**Returns:**
演算子のテキスト表現。
