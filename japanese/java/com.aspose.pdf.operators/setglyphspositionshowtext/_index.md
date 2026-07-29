---
title: "SetGlyphsPositionShowText"
linktitle: "SetGlyphsPositionShowText"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "TJ 演算子を表すクラス（グリフ位置指定でテキストを表示）。"
type: docs
weight: 630
url: /ja/java/com.aspose.pdf.operators/setglyphspositionshowtext/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextShowOperator, com.aspose.pdf.operators.SetGlyphsPositionShowText

```
public class SetGlyphsPositionShowText extends TextShowOperator
```

TJ 演算子を表すクラス（グリフ位置指定でテキストを表示）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText--) | 演算子を初期化します。 |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-) | 演算子を初期化します。 |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-) | 演算子を初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 演算子を処理するためにビジターオブジェクトを受け取ります。 |
| [getGlyphPositions](#getGlyphPositions--) | グリフの位置を返します。 |
| [getText](#getText--) | 演算子引数からテキストを取得します（グリフの位置指定は無視されます）。 |
| [toString](#toString--) | 演算子のテキスト表現を返します。 |

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText--}
```
public SetGlyphsPositionShowText()
```

演算子を初期化します。

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-}
演算子を初期化します。

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-}
演算子を初期化します。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
演算子を処理するためにビジターオブジェクトを受け取ります。

### getGlyphPositions {#getGlyphPositions--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerable< GlyphPosition > getGlyphPositions()
```

グリフの位置を返します。

**Returns:**
GlyphPosition インスタンスのコレクション

### getText {#getText--}
```
public String getText()
```

演算子引数からテキストを取得します（グリフの位置指定は無視されます）。

**Returns:**
文字列値

### toString {#toString--}
```
public String toString()
```

演算子のテキスト表現を返します。

**Returns:**
演算子のテキスト表現。
