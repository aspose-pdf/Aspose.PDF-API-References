---
title: BLSTextElement
linktitle: BLSTextElement
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for block-level text structure elements in logical structure.
type: docs
weight: 20
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/blstextelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class BLSTextElement extends BLSElement implements ITextElement , IAdjustPosition
```

Represents a base class for block-level text structure elements in logical structure.

## Methods

| Method | Description |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Adjust position. |
| [getStructureTextState](#getStructureTextState--) | Gets {@code StructureTextState} object for current element. Value: {@code structureTextState} object for current element. |
| [getTextFragment](#getTextFragment--) |  |
| [setText](#setText-java.lang.String-) | Appends text content to current text element. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Adjust position.

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Gets {@code StructureTextState} object for current element. Value: {@code structureTextState} object for current element.

**Returns:**
Value: StructureTextState object for text structure element.

### getTextFragment {#getTextFragment--}
```
public final TextFragment getTextFragment()
```



### setText {#setText-java.lang.String-}
Appends text content to current text element.
