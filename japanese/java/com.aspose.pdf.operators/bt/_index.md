---
title: "BT"
linktitle: "BT"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "BT 演算子 (Begin of text block) を表すクラス。"
type: docs
weight: 70
url: /ja/java/com.aspose.pdf.operators/bt/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.BlockTextOperator com.aspose.pdf.operators.BT, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.BlockTextOperator com.aspose.pdf.operators.BT, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.BlockTextOperator com.aspose.pdf.operators.BT, com.aspose.pdf.operators.BlockTextOperator, com.aspose.pdf.operators.BT

```
public class BT extends BlockTextOperator
```

BT 演算子 (Begin of text block) を表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BT](#BT--) | 書き込みプログラムのコンストラクタ。 |
| [BT](#BT-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 書き込みプログラムのコンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |
| [toString](#toString--) | 演算子のテキストコードを生成します。 |

### BT {#BT--}
```
public BT()
```

書き込みプログラムのコンストラクタ。

### BT {#BT-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
書き込みプログラムのコンストラクタ。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

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

演算子のテキストコードを生成します。

**Returns:**
演算子のテキスト表現。
