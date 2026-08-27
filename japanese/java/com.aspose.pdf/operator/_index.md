---
title: "Operator"
linktitle: "Operator"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "演算子を表す抽象クラス。"
type: docs
weight: 3180
url: /ja/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

演算子を表す抽象クラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | 内部使用のみ！ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | IOperatorSelector ビジターを受け入れ、演算子の処理を提供します。 |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand インスタンスの名前でオペレーターを作成します。 |
| [equals](#equals-com.aspose.pdf.Operator-) | このインスタンスを指定されたオブジェクトと比較します。 |
| [getCommand](#getCommand--) | コマンドを取得します |
| [getCommandName](#getCommandName--) | オペレーター名を取得します。 |
| [getIndex](#getIndex--) | ページのオペレーターリスト内のオペレーターインデックスを取得します。 |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | オペレーターがテキスト出力（Tj、TJ など）を担当するオペレーターかどうかを判断します。 |
| [setIndex](#setIndex-int-) | ページのオペレーターリスト内のオペレーターインデックスを設定します。 |
| [toString](#toString--) | コマンドとパラメーターを文字列表現に変換します。 |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | このインスタンスを指定されたオブジェクトと比較します。 |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
内部使用のみ！

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
IOperatorSelector ビジターを受け入れ、演算子の処理を提供します。

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand インスタンスの名前でオペレーターを作成します。

### equals {#equals-com.aspose.pdf.Operator-}
このインスタンスを指定されたオブジェクトと比較します。

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

コマンドを取得します

**Returns:**
ICommand オブジェクト

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

オペレーター名を取得します。

**Returns:**
文字列値

### getIndex {#getIndex--}
```
public int getIndex()
```

ページのオペレーターリスト内のオペレーターインデックスを取得します。

**Returns:**
int 値です。

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
オペレーターがテキスト出力（Tj、TJ など）を担当するオペレーターかどうかを判断します。

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

ページのオペレーターリスト内のオペレーターインデックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### toString {#toString--}
```
public String toString()
```

コマンドとパラメーターを文字列表現に変換します。

**Returns:**
オペレーター テキスト

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
このインスタンスを指定されたオブジェクトと比較します。
