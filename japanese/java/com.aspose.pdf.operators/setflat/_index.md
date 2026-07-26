---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "i 演算子を表すクラス（平坦度許容値を設定）。"
type: docs
weight: 620
url: /ja/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

i 演算子を表すクラス（平坦度許容値を設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetFlat](#SetFlat-double-) | 演算子を初期化します。 |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | 演算子クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジタオブジェクトを受け取ります。 |
| [getFlatness](#getFlatness--) | 平坦度を取得します。 |
| [setFlatness](#setFlatness-double-) | 平坦度を設定します。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

演算子を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 平坦度 |  | 平坦度の値。 |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
演算子クラスのコンストラクタです。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジタオブジェクトを受け取ります。

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

平坦度を取得します。

**Returns:**
double 値

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

平坦度を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

内部使用のみ！

**Returns:**
ICommand 値 ICommand オブジェクト
