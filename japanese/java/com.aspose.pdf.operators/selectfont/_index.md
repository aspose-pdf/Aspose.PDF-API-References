---
title: "SelectFont"
linktitle: "SelectFont"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Tf 演算子を表すクラス（テキストのフォントとサイズを設定）。"
type: docs
weight: 470
url: /ja/java/com.aspose.pdf.operators/selectfont/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SelectFont

```
public class SelectFont extends TextStateOperator
```

Tf 演算子を表すクラス（テキストのフォントとサイズを設定）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SelectFont](#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-) | 演算子クラスのコンストラクタです。 |
| [SelectFont](#SelectFont-java.lang.String-double-) | プログラムを書き込むためのコンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getName](#getName--) | フォントの名前を取得します。 |
| [getSize](#getSize--) | テキストのサイズを取得します。 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### SelectFont {#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-}
演算子クラスのコンストラクタです。

### SelectFont {#SelectFont-java.lang.String-double-}
プログラムを書き込むためのコンストラクタ。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getName {#getName--}
```
public String getName()
```

フォントの名前を取得します。

**Returns:**
文字列値

### getSize {#getSize--}
```
public double getSize()
```

テキストのサイズを取得します。

**Returns:**
double 値

### toString {#toString--}
```
public String toString()
```

演算子のテキスト表現を返します。

**Returns:**
演算子のテキスト表現。
