---
title: "SetColorSpace"
linktitle: "SetColorSpace"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "cs 演算子を表すクラス（非ストローク操作のためのカラースペースを設定）。"
type: docs
weight: 580
url: /ja/java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpace, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpace

```
public class SetColorSpace extends Operator
```

cs 演算子を表すクラス（非ストローク操作のためのカラースペースを設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetColorSpace](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-) | 演算子クラスのコンストラクタです。 |
| [SetColorSpace](#SetColorSpace-java.lang.String-) | 演算子を初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getCommandName](#getCommandName--) | コマンド名を取得します。 |
| [getName](#getName--) | カラースペース名を取得します。 |
| [setName](#setName-java.lang.String-) | カラースペース名を設定します。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |

### SetColorSpace {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-}
演算子クラスのコンストラクタです。

### SetColorSpace {#SetColorSpace-java.lang.String-}
演算子を初期化します。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

コマンド名を取得します。

**Returns:**
文字列値

### getName {#getName--}
```
public String getName()
```

カラースペース名を取得します。

**Returns:**
文字列値

### setName {#setName-java.lang.String-}
カラースペース名を設定します。

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

内部使用のみ！

**Returns:**
ICommand 値 ICommand オブジェクト
