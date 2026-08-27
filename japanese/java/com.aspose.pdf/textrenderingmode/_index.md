---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストレンダリングモード（Tmode）は、テキストを表示する際にグリフのアウトラインをストローク、塗りつぶし、クリッピング境界として使用するか、またはその3つの組み合わせのいずれかになるかを決定します。"
type: docs
weight: 5240
url: /ja/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

テキストレンダリングモード（Tmode）は、テキストを表示する際にグリフのアウトラインをストローク、塗りつぶし、クリッピング境界として使用するか、またはその3つの組み合わせのいずれかになるかを決定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | クリッピング用にパスにテキストを追加します。 |
| [FillText](#FillText) | テキストを塗りつぶします。 |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | テキストを塗りつぶし、クリッピング用にパスに追加します（9.3.6、"Text Rendering Mode," を参照）。 |
| [FillThenStrokeText](#FillThenStrokeText) | テキストを塗りつぶし、次に輪郭を描画します。 |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | テキストを塗りつぶし、次に輪郭を描画し、クリッピング用にパスに追加します。 |
| [Invisible](#Invisible) | テキストを塗りつぶすことも輪郭を描画することもありません（不可視）。 |
| [StrokeText](#StrokeText) | テキストに輪郭を描画します。 |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | テキストに輪郭を描画し、クリッピング用にパスに追加します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

クリッピング用にパスにテキストを追加します。

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

テキストを塗りつぶします。

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

テキストを塗りつぶし、クリッピング用にパスに追加します（9.3.6、"Text Rendering Mode," を参照）。

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

テキストを塗りつぶし、次に輪郭を描画します。

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

テキストを塗りつぶし、次に輪郭を描画し、クリッピング用にパスに追加します。

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

テキストを塗りつぶすことも輪郭を描画することもありません（不可視）。

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

テキストに輪郭を描画します。

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

テキストに輪郭を描画し、クリッピング用にパスに追加します。

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### valueOf {#valueOf-java.lang.String-}
指定された名前でこの型の列挙定数を返します。

### values {#values--}
```
public static TextRenderingMode [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列
