---
title: "SetColorSpaceStroke"
linktitle: "SetColorSpaceStroke"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "CS 演算子を表すクラス（ストローク操作のためのカラーを設定）。"
type: docs
weight: 590
url: /ja/java/com.aspose.pdf.operators/setcolorspacestroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpaceStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpaceStroke

```
public class SetColorSpaceStroke extends Operator
```

CS 演算子を表すクラス（ストローク操作のためのカラーを設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetColorSpaceStroke](#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-) | 演算子クラスのコンストラクタです。 |
| [SetColorSpaceStroke](#SetColorSpaceStroke-java.lang.String-) | 演算子を初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジタオブジェクトを受け取ります。 |
| [getName](#getName--) | カラースペース名を取得します。 |
| [setName](#setName-java.lang.String-) | カラースペース名を設定します。 |
| [toCommand](#toCommand--) | 内部使用のみ！ |

### SetColorSpaceStroke {#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-}
演算子クラスのコンストラクタです。

### SetColorSpaceStroke {#SetColorSpaceStroke-java.lang.String-}
演算子を初期化します。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジタオブジェクトを受け取ります。

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
