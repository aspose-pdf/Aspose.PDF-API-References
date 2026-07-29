---
title: "BX"
linktitle: "BX"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "BX 演算子 (begin compatibility section) を表すクラス。"
type: docs
weight: 80
url: /ja/java/com.aspose.pdf.operators/bx/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.BX, com.aspose.pdf.Operator, com.aspose.pdf.operators.BX

```
public class BX extends Operator
```

BX 演算子 (begin compatibility section) を表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BX](#BX--) | 演算子を初期化します。 |
| [BX](#BX-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 演算子を初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getCommandName](#getCommandName--) | コマンド名のテキスト表現を返します。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### BX {#BX--}
```
public BX()
```

演算子を初期化します。

### BX {#BX-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
演算子を初期化します。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

コマンド名のテキスト表現を返します。

**Returns:**
文字列値

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
演算子のテキスト表現。
