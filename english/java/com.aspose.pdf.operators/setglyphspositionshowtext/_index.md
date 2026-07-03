---
title: SetGlyphsPositionShowText
second_title: Aspose.PDF for Java API Reference
description: Class representing TJ operator (show text with glyph positioning).
type: docs
weight: 630
url: /java/com.aspose.pdf.operators/setglyphspositionshowtext/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextShowOperator, com.aspose.pdf.operators.SetGlyphsPositionShowText

```
public class SetGlyphsPositionShowText extends TextShowOperator
```

Class representing TJ operator (show text with glyph positioning).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText--) | Initializes operator. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-) | Initializes operator. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-) | Initializes operator. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getGlyphPositions](#getGlyphPositions--) | Returns positions of glyphs. |
| [getText](#getText--) | Gets text from operator argument (glyph positioning is ignored). |
| [toString](#toString--) | Returns text representation of operator. |

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText--}
```
public SetGlyphsPositionShowText()
```

Initializes operator.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-}
Initializes operator.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-}
Initializes operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getGlyphPositions {#getGlyphPositions--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerable< GlyphPosition > getGlyphPositions()
```

Returns positions of glyphs.

**Returns:**
collection of GlyphPosition instances

### getText {#getText--}
```
public String getText()
```

Gets text from operator argument (glyph positioning is ignored).

**Returns:**
String value

### toString {#toString--}
```
public String toString()
```

Returns text representation of operator.

**Returns:**
Text representation of operator.
