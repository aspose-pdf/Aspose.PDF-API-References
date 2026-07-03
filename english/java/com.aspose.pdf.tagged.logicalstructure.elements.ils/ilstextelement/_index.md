---
title: ILSTextElement
linktitle: ILSTextElement
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for inline-level text structure elements in logical structure.
type: docs
weight: 60
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.ils/ilstextelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSTextElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class ILSTextElement extends ILSElement implements ITextElement , IAdjustPosition
```

Represents a base class for inline-level text structure elements in logical structure.

## Methods

| Method | Description |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Adjust position. |
| [getStructureTextState](#getStructureTextState--) | Gets {@code StructureTextState} object for current element. Value: {@code StructureTextState} object for current element. |
| [setText](#setText-java.lang.String-) | Appends text content to current text element. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Adjust position.

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Gets {@code StructureTextState} object for current element. Value: {@code StructureTextState} object for current element.

**Returns:**
Value: StructureTextState object for text structure element.

### setText {#setText-java.lang.String-}
Appends text content to current text element.
