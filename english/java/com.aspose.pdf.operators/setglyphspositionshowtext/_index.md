---
title: SetGlyphsPositionShowText
second_title: Aspose.PDF for Java API Reference
description: Class representing TJ operator show text with glyph positioning.
type: docs
weight: 69
url: /java/com.aspose.pdf.operators/setglyphspositionshowtext/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextShowOperator](../../com.aspose.pdf.operators/textshowoperator)
```
public class SetGlyphsPositionShowText extends TextShowOperator
```

Class representing TJ operator (show text with glyph positioning).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetGlyphsPositionShowText()](#SetGlyphsPositionShowText--) | Initializes operator. |
| [SetGlyphsPositionShowText(int index, ICommand command)](#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetGlyphsPositionShowText(System.Collections.Generic.IGenericEnumerable<GlyphPosition> glyphPositions)](#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.pdf.operators.GlyphPosition--) | Constructor for TJ operator. |
## Methods

| Method | Description |
| --- | --- |
| [getGlyphPositions()](#getGlyphPositions--) | Returns positions of glyphs. |
| [getText()](#getText--) | Gets text from operator argument (glyph positioning is ignored). |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
### SetGlyphsPositionShowText() {#SetGlyphsPositionShowText--}
```
public SetGlyphsPositionShowText()
```


Initializes operator.

### SetGlyphsPositionShowText(int index, ICommand command) {#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetGlyphsPositionShowText(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetGlyphsPositionShowText(System.Collections.Generic.IGenericEnumerable<GlyphPosition> glyphPositions) {#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.pdf.operators.GlyphPosition--}
```
public SetGlyphsPositionShowText(System.Collections.Generic.IGenericEnumerable<GlyphPosition> glyphPositions)
```


Constructor for TJ operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| glyphPositions | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.pdf.operators.GlyphPosition> | List of Glyph Positions. |

### getGlyphPositions() {#getGlyphPositions--}
```
public System.Collections.Generic.IGenericEnumerable<GlyphPosition> getGlyphPositions()
```


Returns positions of glyphs.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.pdf.operators.GlyphPosition> - collection of GlyphPosition instances
### getText() {#getText--}
```
public String getText()
```


Gets text from operator argument (glyph positioning is ignored).

**Returns:**
java.lang.String - String value
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

### toString() {#toString--}
```
public String toString()
```


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of operator.
