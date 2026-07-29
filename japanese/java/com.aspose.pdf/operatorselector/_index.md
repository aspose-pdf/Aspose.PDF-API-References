---
title: "OperatorSelector"
linktitle: "OperatorSelector"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは Visitor テンプレートの考え方を用いて演算子を選択するために使用されます。"
type: docs
weight: 3200
url: /ja/java/com.aspose.pdf/operatorselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OperatorSelector

**All Implemented Interfaces:**
IOperatorSelector

```
public final class OperatorSelector extends Object implements IOperatorSelector
```

このクラスは Visitor テンプレートの考え方を用いて演算子を選択するために使用されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OperatorSelector](#OperatorSelector--) | 新しい {@code Selector} クラスのインスタンスを初期化します。 |
| [OperatorSelector](#OperatorSelector-com.aspose.pdf.Operator-) | 新しい {@code Selector} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSelected](#getSelected--) | 選択されたオブジェクトのリストです。 |
| [visit](#visit-com.aspose.pdf.operators.BDC-) | BDC 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.BI-) | BI 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.BMC-) | BMC 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.BT-) | BT 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.BX-) | BX 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.Clip-) | W 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.ClosePath-) | h 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | b* 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | b 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.ClosePathStroke-) | s 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | cm 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.CurveTo-) | c 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.CurveTo1-) | v 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.CurveTo2-) | y 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.Do-) | Do 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.DP-) | DP 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.EI-) | EI 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.EMC-) | EMC 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.EndPath-) | n 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.EOClip-) | W* 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.EOFill-) | f* 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.EOFillStroke-) | B* 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.ET-) | ET 演算子を訪問/選択します。 |
| [visit](#visit-com.aspose.pdf.operators.EX-) | 訪問/選択 EX 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.Fill-) | 訪問/選択 f 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.FillStroke-) | 訪問/選択 B 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.GRestore-) | 訪問/選択 Q 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.GS-) | 訪問/選択 gs 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.GSave-) | 訪問/選択 q 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.ID-) | 訪問/選択 ID 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.LineTo-) | 訪問/選択 l 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPosition-) | 訪問/選択 Td 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | 訪問/選択 TD 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.MoveTo-) | 訪問/選択 m 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLine-) | 訪問/選択 T* 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | 訪問/選択 ' 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.MP-) | 訪問/選択 MP 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.ObsoleteFill-) | 訪問/選択 F 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.Re-) | 訪問/選択 re 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.SelectFont-) | 訪問/選択 Tf 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | 訪問/選択 scn 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | 訪問/選択 SCN 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | 訪問/選択 Tc 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidth-) | 訪問/選択 d0 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | 訪問/選択 d1 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColor-) | 訪問/選択 k 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | 訪問/選択 K 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.SetColor-) | 訪問/選択 sc 演算子。 |
| [visit](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | 訪問/選択 ri 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpace-) | 訪問/選択 cs 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | 訪問/選択 CS 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetColorStroke-) | 訪問/選択 SC 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetDash-) | 訪問/選択 d 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetFlat-) | 訪問/選択 i 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | 訪問/選択 TJ 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetGray-) | 訪問/選択 g 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetGrayStroke-) | 訪問/選択 G 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | 訪問/選択 Tz 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetLineCap-) | 訪問/選択 J 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetLineJoin-) | 訪問/選択 j 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetLineWidth-) | 訪問/選択 w 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetMiterLimit-) | 訪問/選択 M 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColor-) | 訪問/選択 rg 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | 訪問/選択 RG 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | 訪問/選択 '' 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetTextLeading-) | 訪問/選択 TL 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetTextMatrix-) | 訪問/選択 Tm 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | 訪問/選択 Tr 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetTextRise-) | 訪問/選択 Ts 演算子. |
| [visit](#visit-com.aspose.pdf.operators.SetWordSpacing-) | 訪問/選択 Tw 演算子. |
| [visit](#visit-com.aspose.pdf.operators.ShFill-) | 訪問/選択 sh 演算子. |
| [visit](#visit-com.aspose.pdf.operators.ShowText-) | 訪問/選択 Tj 演算子. |
| [visit](#visit-com.aspose.pdf.operators.Stroke-) | 訪問/選択 S 演算子. |
| [visit](#visit-com.aspose.pdf.operators.TextOperator-) | 任意のテキストオペレーターを訪問/選択します。 |

### OperatorSelector {#OperatorSelector--}
```
public OperatorSelector()
```

新しい {@code Selector} クラスのインスタンスを初期化します。

### OperatorSelector {#OperatorSelector-com.aspose.pdf.Operator-}
新しい {@code Selector} クラスのインスタンスを初期化します。

### getSelected {#getSelected--}
```
public List < Operator > getSelected()
```

選択されたオブジェクトのリストです。

**Returns:**
Operator インスタンスのリスト

### visit {#visit-com.aspose.pdf.operators.BDC-}
BDC 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.BI-}
BI 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.BMC-}
BMC 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.BT-}
BT 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.BX-}
BX 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.Clip-}
W 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.ClosePath-}
h 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
b* 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
b 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.ClosePathStroke-}
s 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
cm 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.CurveTo-}
c 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.CurveTo1-}
v 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.CurveTo2-}
y 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.Do-}
Do 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.DP-}
DP 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.EI-}
EI 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.EMC-}
EMC 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.EndPath-}
n 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.EOClip-}
W* 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.EOFill-}
f* 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.EOFillStroke-}
B* 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.ET-}
ET 演算子を訪問/選択します。

### visit {#visit-com.aspose.pdf.operators.EX-}
訪問/選択 EX 演算子。

### visit {#visit-com.aspose.pdf.operators.Fill-}
訪問/選択 f 演算子。

### visit {#visit-com.aspose.pdf.operators.FillStroke-}
訪問/選択 B 演算子。

### visit {#visit-com.aspose.pdf.operators.GRestore-}
訪問/選択 Q 演算子。

### visit {#visit-com.aspose.pdf.operators.GS-}
訪問/選択 gs 演算子。

### visit {#visit-com.aspose.pdf.operators.GSave-}
訪問/選択 q 演算子。

### visit {#visit-com.aspose.pdf.operators.ID-}
訪問/選択 ID 演算子。

### visit {#visit-com.aspose.pdf.operators.LineTo-}
訪問/選択 l 演算子。

### visit {#visit-com.aspose.pdf.operators.MoveTextPosition-}
訪問/選択 Td 演算子。

### visit {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
訪問/選択 TD 演算子。

### visit {#visit-com.aspose.pdf.operators.MoveTo-}
訪問/選択 m 演算子。

### visit {#visit-com.aspose.pdf.operators.MoveToNextLine-}
訪問/選択 T* 演算子。

### visit {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
訪問/選択 ' 演算子。

### visit {#visit-com.aspose.pdf.operators.MP-}
訪問/選択 MP 演算子。

### visit {#visit-com.aspose.pdf.operators.ObsoleteFill-}
訪問/選択 F 演算子。

### visit {#visit-com.aspose.pdf.operators.Re-}
訪問/選択 re 演算子。

### visit {#visit-com.aspose.pdf.operators.SelectFont-}
訪問/選択 Tf 演算子。

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
訪問/選択 scn 演算子。

### visit {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
訪問/選択 SCN 演算子。

### visit {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
訪問/選択 Tc 演算子。

### visit {#visit-com.aspose.pdf.operators.SetCharWidth-}
訪問/選択 d0 演算子。

### visit {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
訪問/選択 d1 演算子。

### visit {#visit-com.aspose.pdf.operators.SetCMYKColor-}
訪問/選択 k 演算子。

### visit {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
訪問/選択 K 演算子。

### visit {#visit-com.aspose.pdf.operators.SetColor-}
訪問/選択 sc 演算子。

### visit {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
訪問/選択 ri 演算子.

### visit {#visit-com.aspose.pdf.operators.SetColorSpace-}
訪問/選択 cs 演算子.

### visit {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
訪問/選択 CS 演算子.

### visit {#visit-com.aspose.pdf.operators.SetColorStroke-}
訪問/選択 SC 演算子.

### visit {#visit-com.aspose.pdf.operators.SetDash-}
訪問/選択 d 演算子.

### visit {#visit-com.aspose.pdf.operators.SetFlat-}
訪問/選択 i 演算子.

### visit {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
訪問/選択 TJ 演算子.

### visit {#visit-com.aspose.pdf.operators.SetGray-}
訪問/選択 g 演算子.

### visit {#visit-com.aspose.pdf.operators.SetGrayStroke-}
訪問/選択 G 演算子.

### visit {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
訪問/選択 Tz 演算子.

### visit {#visit-com.aspose.pdf.operators.SetLineCap-}
訪問/選択 J 演算子.

### visit {#visit-com.aspose.pdf.operators.SetLineJoin-}
訪問/選択 j 演算子.

### visit {#visit-com.aspose.pdf.operators.SetLineWidth-}
訪問/選択 w 演算子.

### visit {#visit-com.aspose.pdf.operators.SetMiterLimit-}
訪問/選択 M 演算子.

### visit {#visit-com.aspose.pdf.operators.SetRGBColor-}
訪問/選択 rg 演算子.

### visit {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
訪問/選択 RG 演算子.

### visit {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
訪問/選択 '' 演算子.

### visit {#visit-com.aspose.pdf.operators.SetTextLeading-}
訪問/選択 TL 演算子.

### visit {#visit-com.aspose.pdf.operators.SetTextMatrix-}
訪問/選択 Tm 演算子.

### visit {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
訪問/選択 Tr 演算子.

### visit {#visit-com.aspose.pdf.operators.SetTextRise-}
訪問/選択 Ts 演算子.

### visit {#visit-com.aspose.pdf.operators.SetWordSpacing-}
訪問/選択 Tw 演算子.

### visit {#visit-com.aspose.pdf.operators.ShFill-}
訪問/選択 sh 演算子.

### visit {#visit-com.aspose.pdf.operators.ShowText-}
訪問/選択 Tj 演算子.

### visit {#visit-com.aspose.pdf.operators.Stroke-}
訪問/選択 S 演算子.

### visit {#visit-com.aspose.pdf.operators.TextOperator-}
任意のテキストオペレーターを訪問/選択します。
