---
title: "実行"
linktitle: "実行"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Do 演算子 (Invoke XObject) を表すクラス。"
type: docs
weight: 180
url: /ja/java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

Do 演算子 (Invoke XObject) を表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Do](#Do--) | 新しい Do 演算子を構築します。すべての Do 演算子を取得するために使用されます。つまり、引数名をチェックしません。 |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | 新しい Do 演算子を構築します。すべての Do 演算子を取得するために使用されます。つまり、引数名をチェックしません。 |
| [Do](#Do-java.lang.String-) | 新しい Do 演算子を構築します。すべての Do 演算子を取得するために使用されます。つまり、引数名をチェックしません。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getCommandName](#getCommandName--) | コマンド名を取得します |
| [getName](#getName--) | 演算子の XObject 引数の名前を取得します。 |
| [setName](#setName-java.lang.String-) | 演算子の XObject 引数の名前を設定します。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### Do {#Do--}
```
public Do()
```

新しい Do 演算子を構築します。すべての Do 演算子を取得するために使用されます。つまり、引数名をチェックしません。

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
新しい Do 演算子を構築します。すべての Do 演算子を取得するために使用されます。つまり、引数名をチェックしません。

### Do {#Do-java.lang.String-}
新しい Do 演算子を構築します。すべての Do 演算子を取得するために使用されます。つまり、引数名をチェックしません。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

コマンド名を取得します

**Returns:**
文字列値

### getName {#getName--}
```
public String getName()
```

演算子の XObject 引数の名前を取得します。

**Returns:**
文字列値

### setName {#setName-java.lang.String-}
演算子の XObject 引数の名前を設定します。

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
