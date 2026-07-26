---
title: "DP"
linktitle: "DP"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "DP 演算子 (designamte marked content point) を表すクラス。"
type: docs
weight: 190
url: /ja/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

DP 演算子 (designamte marked content point) を表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | 演算子クラスのコンストラクタです。 |
| [DP](#DP-java.lang.String-) | 演算子を初期化します。 |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getPropertiesDictionary](#getPropertiesDictionary--) | プロパティ辞書を取得します |
| [getTag](#getTag--) | マークされたコンテンツタグを取得します |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | プロパティの辞書を設定します |
| [setTag](#setTag-java.lang.String-) | マークされたコンテンツタグを設定します |
| [toCommand](#toCommand--) | 内部使用のみ！ |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
演算子クラスのコンストラクタです。

### DP {#DP-java.lang.String-}
演算子を初期化します。

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

プロパティ辞書を取得します

**Returns:**
IPdfDictionary の値

### getTag {#getTag--}
```
public String getTag()
```

マークされたコンテンツタグを取得します

**Returns:**
文字列値

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
プロパティの辞書を設定します

### setTag {#setTag-java.lang.String-}
マークされたコンテンツタグを設定します

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
