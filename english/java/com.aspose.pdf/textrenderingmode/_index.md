---
title: TextRenderingMode
linktitle: TextRenderingMode
second_title: Aspose.PDF for Java API Reference
description: The text rendering mode, Tmode, determines whether showing text shall cause glyph outlines to be stroked, filled, used as a clipping boundary, or some combination of the three.
type: docs
weight: 5240
url: /java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

The text rendering mode, Tmode, determines whether showing text shall cause glyph outlines to be stroked, filled, used as a clipping boundary, or some combination of the three.

## Fields

| Field | Description |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | Add text to path for clipping. |
| [FillText](#FillText) | Fill text. |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | Fill text and add to path for clipping (see 9.3.6, "Text Rendering Mode,"). |
| [FillThenStrokeText](#FillThenStrokeText) | Fill, then stroke text. |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | Fill, then stroke text and add to path for clipping. |
| [Invisible](#Invisible) | Neither fill nor stroke text (invisible). |
| [StrokeText](#StrokeText) | Stroke text. |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | Stroke text and add to path for clipping. |

## Methods

| Method | Description |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

Add text to path for clipping.

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

Fill text.

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

Fill text and add to path for clipping (see 9.3.6, "Text Rendering Mode,").

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

Fill, then stroke text.

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

Fill, then stroke text and add to path for clipping.

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

Neither fill nor stroke text (invisible).

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

Stroke text.

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

Stroke text and add to path for clipping.

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static TextRenderingMode [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
