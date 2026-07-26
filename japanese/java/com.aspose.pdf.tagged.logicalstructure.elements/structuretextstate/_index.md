---
title: "StructureTextState"
linktitle: "StructureTextState"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト構造要素および TaggedContent (ITextElement、ITaggedContent) のテキスト状態設定を表します。"
type: docs
weight: 120
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState

```
public class StructureTextState extends Object
```

テキスト構造要素および TaggedContent (ITextElement、ITaggedContent) のテキスト状態設定を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [StructureTextState](#StructureTextState--) | デフォルトコンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [createTextState](#createTextState--) | テキスト状態を作成 |
| [getBackgroundColor](#getBackgroundColor--) | テキストの背景色を取得または設定します。null にできます。null を使用して、親構造要素から {@code BackgroundColor} プロパティを継承します。 |
| [getCharacterSpacing](#getCharacterSpacing--) | テキストの文字間隔を取得または設定します。null にできます。null を使用して、親構造要素から {@code CharacterSpacing} プロパティを継承します。 |
| [getFont](#getFont--) | テキストのフォントを取得または設定します。null にできます。null を使用して、親構造要素から {@code Font} プロパティを継承します。 |
| [getFontSize](#getFontSize--) | テキストのフォントサイズを取得または設定します。null にできます。null を使用して、親構造要素から {@code FontSize} プロパティを継承します。 |
| [getFontStyle](#getFontStyle--) | テキストのフォントスタイルを取得または設定します。null にできます。null を使用して、親構造要素から {@code FontStyle} プロパティを継承します。 |
| [getForegroundColor](#getForegroundColor--) | テキストの前景色を取得または設定します。null にできます。null を使用して、親構造要素から {@code ForegroundColor} プロパティを継承します。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 段落の水平揃えを取得または設定します |
| [getHorizontalScaling](#getHorizontalScaling--) | テキストの水平スケーリングを取得または設定します。null にできます。null を使用して、親構造要素から {@code HorizontalScaling} プロパティを継承します。 |
| [getLineSpacing](#getLineSpacing--) | テキストの行間隔を取得または設定します。null にできます。null を使用して、親構造要素から {@code LineSpacing} プロパティを継承します。 |
| [getMarginInfo](#getMarginInfo--) | ブロック構造要素の余白を取得または設定します。 |
| [getStrikeOut](#getStrikeOut--) | テキストの打ち消し線を取得または設定します。null にできます。null を使用して、親構造要素から {@code StrikeOut} プロパティを継承します。 |
| [getSubscript](#getSubscript--) | テキストの下付き文字を取得または設定します。null にできます。null を使用して、親構造要素から {@code Subscript} プロパティを継承します。 |
| [getSuperscript](#getSuperscript--) | テキストの上付き文字を取得または設定します。null にできます。null を使用して、親構造要素から {@code Superscript} プロパティを継承します。 |
| [getUnderline](#getUnderline--) | テキストの下線を取得または設定します。null にできます。null を使用して、親構造要素から {@code Underline} プロパティを継承します。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 段落の垂直揃えを取得または設定します |
| [getWordSpacing](#getWordSpacing--) | テキストの単語間隔を取得または設定します。null にすることができます。null を使用して、親構造要素から {@code WordSpacing} プロパティを継承します。 |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | この段落が次の列に配置されるかどうかを示すブール値を取得または設定します。デフォルトは false です。 |
| [isInLineParagraph](#isInLineParagraph--) | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。 |
| [isInNewPage](#isInNewPage--) | この段落が新しいページで生成されるように強制するブール値を取得または設定します。デフォルトは false です。 |
| [isKeptWithNext](#isKeptWithNext--) | 現在の段落が次の段落と同じページに残るかどうかを示すブール値を取得または設定します。デフォルトは false です。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | テキストの背景色を取得または設定します。null にできます。null を使用して、親構造要素から {@code BackgroundColor} プロパティを継承します。 |
| [setCharacterSpacing](#setCharacterSpacing-com.aspose.ms.System.Nullable-) | テキストの文字間隔を取得または設定します。 |
| [setFont](#setFont-com.aspose.pdf.Font-) | テキストのフォントを取得または設定します。null にできます。null を使用して、親構造要素から {@code Font} プロパティを継承します。 |
| [setFontSize](#setFontSize-com.aspose.ms.System.Nullable-) | テキストのフォントサイズを取得または設定します。 |
| [setFontStyle](#setFontStyle-com.aspose.ms.System.Nullable-) | テキストのフォントスタイルを取得または設定します。 |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | テキストの前景色を取得または設定します。null にできます。null を使用して、親構造要素から {@code ForegroundColor} プロパティを継承します。 |
| [setHorizontalScaling](#setHorizontalScaling-com.aspose.ms.System.Nullable-) | テキストの水平スケーリングを取得または設定します。 |
| [setLineSpacing](#setLineSpacing-com.aspose.ms.System.Nullable-) | テキストの行間隔を取得または設定します。 |
| [setMarginInfo](#setMarginInfo-com.aspose.pdf.MarginInfo-) | ブロック構造要素の余白を取得または設定します。 |
| [setStrikeOut](#setStrikeOut-com.aspose.ms.System.Nullable-) | テキストの取り消し線を取得または設定します。 |
| [setSubscript](#setSubscript-com.aspose.ms.System.Nullable-) | テキストの下付き文字を取得または設定します。 |
| [setSuperscript](#setSuperscript-com.aspose.ms.System.Nullable-) | テキストの上付き文字を取得または設定します。 |
| [setUnderline](#setUnderline-com.aspose.ms.System.Nullable-) | テキストの下線を取得または設定します。 |
| [setWordSpacing](#setWordSpacing-com.aspose.ms.System.Nullable-) | テキストの単語間隔を取得または設定します。 |
| [update](#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-) | 要素を更新する |

### StructureTextState {#StructureTextState--}
```
public StructureTextState()
```

デフォルトコンストラクタ

### createTextState {#createTextState--}
```
public final TextState createTextState()
```

テキスト状態を作成

**Returns:**
TextState インスタンス

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

テキストの背景色を取得または設定します。null にできます。null を使用して、親構造要素から {@code BackgroundColor} プロパティを継承します。

**Returns:**
Color インスタンス

### getCharacterSpacing {#getCharacterSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getCharacterSpacing()
```

テキストの文字間隔を取得または設定します。null にできます。null を使用して、親構造要素から {@code CharacterSpacing} プロパティを継承します。

**Returns:**
浮動小数点配列

### getFont {#getFont--}
```
public final Font getFont()
```

テキストのフォントを取得または設定します。null にできます。null を使用して、親構造要素から {@code Font} プロパティを継承します。

**Returns:**
フォント インスタンス

### getFontSize {#getFontSize--}
```
public final com.aspose.ms.System.Nullable< Float > getFontSize()
```

テキストのフォントサイズを取得または設定します。null にできます。null を使用して、親構造要素から {@code FontSize} プロパティを継承します。

**Returns:**
浮動小数点配列

### getFontStyle {#getFontStyle--}
```
public final com.aspose.ms.System.Nullable< Integer > getFontStyle()
```

テキストのフォントスタイルを取得または設定します。null にできます。null を使用して、親構造要素から {@code FontStyle} プロパティを継承します。

**Returns:**
整数配列

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

テキストの前景色を取得または設定します。null にできます。null を使用して、親構造要素から {@code ForegroundColor} プロパティを継承します。

**Returns:**
Color インスタンス

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public final com.aspose.ms.System.Nullable< HorizontalAlignment > getHorizontalAlignment()
```

段落の水平揃えを取得または設定します

**Returns:**
HorizontalAlignment 要素

### getHorizontalScaling {#getHorizontalScaling--}
```
public final com.aspose.ms.System.Nullable< Float > getHorizontalScaling()
```

テキストの水平スケーリングを取得または設定します。null にできます。null を使用して、親構造要素から {@code HorizontalScaling} プロパティを継承します。

**Returns:**
浮動小数点配列

### getLineSpacing {#getLineSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getLineSpacing()
```

テキストの行間隔を取得または設定します。null にできます。null を使用して、親構造要素から {@code LineSpacing} プロパティを継承します。

**Returns:**
浮動小数点配列

### getMarginInfo {#getMarginInfo--}
```
@Deprecated public final MarginInfo getMarginInfo()
```

ブロック構造要素の余白を取得または設定します。

**Returns:**
MarginInfo インスタンス @deprecated 位置設定を設定するには IAdjustPosition.AdjustPosition(PositionSettings positionSettings) メソッドを使用してください

### getStrikeOut {#getStrikeOut--}
```
public final com.aspose.ms.System.Nullable< Boolean > getStrikeOut()
```

テキストの打ち消し線を取得または設定します。null にできます。null を使用して、親構造要素から {@code StrikeOut} プロパティを継承します。

**Returns:**
ブール配列

### getSubscript {#getSubscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSubscript()
```

テキストの下付き文字を取得または設定します。null にできます。null を使用して、親構造要素から {@code Subscript} プロパティを継承します。

**Returns:**
ブール配列

### getSuperscript {#getSuperscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSuperscript()
```

テキストの上付き文字を取得または設定します。null にできます。null を使用して、親構造要素から {@code Superscript} プロパティを継承します。

**Returns:**
ブール配列

### getUnderline {#getUnderline--}
```
public final com.aspose.ms.System.Nullable< Boolean > getUnderline()
```

テキストの下線を取得または設定します。null にできます。null を使用して、親構造要素から {@code Underline} プロパティを継承します。

**Returns:**
ブール配列

### getVerticalAlignment {#getVerticalAlignment--}
```
public final com.aspose.ms.System.Nullable< VerticalAlignment > getVerticalAlignment()
```

段落の垂直揃えを取得または設定します

**Returns:**
VerticalAlignment 要素

### getWordSpacing {#getWordSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getWordSpacing()
```

テキストの単語間隔を取得または設定します。null にすることができます。null を使用して、親構造要素から {@code WordSpacing} プロパティを継承します。

**Returns:**
浮動小数点配列

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public final com.aspose.ms.System.Nullable< Boolean > isFirstParagraphInColumn()
```

この段落が次の列に配置されるかどうかを示すブール値を取得または設定します。デフォルトは false です。

**Returns:**
ブール値

### isInLineParagraph {#isInLineParagraph--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInLineParagraph()
```

段落がインラインであるかどうかを取得または設定します。デフォルトは false です。

**Returns:**
ブール値

### isInNewPage {#isInNewPage--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInNewPage()
```

この段落が新しいページで生成されるように強制するブール値を取得または設定します。デフォルトは false です。

**Returns:**
ブール値

### isKeptWithNext {#isKeptWithNext--}
```
public final com.aspose.ms.System.Nullable< Boolean > isKeptWithNext()
```

現在の段落が次の段落と同じページに残るかどうかを示すブール値を取得または設定します。デフォルトは false です。

**Returns:**
ブール値

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
テキストの背景色を取得または設定します。null にできます。null を使用して、親構造要素から {@code BackgroundColor} プロパティを継承します。

### setCharacterSpacing {#setCharacterSpacing-com.aspose.ms.System.Nullable-}
テキストの文字間隔を取得または設定します。

### setFont {#setFont-com.aspose.pdf.Font-}
テキストのフォントを取得または設定します。null にできます。null を使用して、親構造要素から {@code Font} プロパティを継承します。

### setFontSize {#setFontSize-com.aspose.ms.System.Nullable-}
テキストのフォントサイズを取得または設定します。

### setFontStyle {#setFontStyle-com.aspose.ms.System.Nullable-}
テキストのフォントスタイルを取得または設定します。

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
テキストの前景色を取得または設定します。null にできます。null を使用して、親構造要素から {@code ForegroundColor} プロパティを継承します。

### setHorizontalScaling {#setHorizontalScaling-com.aspose.ms.System.Nullable-}
テキストの水平スケーリングを取得または設定します。

### setLineSpacing {#setLineSpacing-com.aspose.ms.System.Nullable-}
テキストの行間隔を取得または設定します。

### setMarginInfo {#setMarginInfo-com.aspose.pdf.MarginInfo-}
ブロック構造要素の余白を取得または設定します。

### setStrikeOut {#setStrikeOut-com.aspose.ms.System.Nullable-}
テキストの取り消し線を取得または設定します。

### setSubscript {#setSubscript-com.aspose.ms.System.Nullable-}
テキストの下付き文字を取得または設定します。

### setSuperscript {#setSuperscript-com.aspose.ms.System.Nullable-}
テキストの上付き文字を取得または設定します。

### setUnderline {#setUnderline-com.aspose.ms.System.Nullable-}
テキストの下線を取得または設定します。

### setWordSpacing {#setWordSpacing-com.aspose.ms.System.Nullable-}
テキストの単語間隔を取得または設定します。

### update {#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-}
要素を更新する
