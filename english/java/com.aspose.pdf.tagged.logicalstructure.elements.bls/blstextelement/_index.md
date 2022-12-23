---
title: BLSTextElement
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for block-level text structure elements in logical structure.
type: docs
weight: 11
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/blstextelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/blselement)

**All Implemented Interfaces:**
[com.aspose.pdf.tagged.logicalstructure.elements.ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement)
```
public abstract class BLSTextElement extends BLSElement implements ITextElement
```

Represents a base class for block-level text structure elements in logical structure.
## Methods

| Method | Description |
| --- | --- |
| [getTextFragment()](#getTextFragment--) |  |
| [getStructureTextState()](#getStructureTextState--) | Gets  StructureTextState  object for current element. |
| [setText(String text)](#setText-java.lang.String-) | Appends text content to current text element. |
### getTextFragment() {#getTextFragment--}
```
public final TextFragment getTextFragment()
```




**Returns:**
[TextFragment](../../com.aspose.pdf/textfragment)
### getStructureTextState() {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```


Gets  StructureTextState  object for current element.

Value:  structureTextState  object for current element.

**Returns:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate)
### setText(String text) {#setText-java.lang.String-}
```
public final void setText(String text)
```


Appends text content to current text element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content |

