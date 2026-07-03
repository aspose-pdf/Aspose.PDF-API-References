---
title: LinkElement
second_title: Aspose.PDF for Java API Reference
description: Represents Link structure element in logical structure.
type: docs
weight: 70
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public final class LinkElement extends AnnotationElement implements ITextElement , IAdjustPosition
```

Represents Link structure element in logical structure.

## Constructors

| Constructor | Description |
| --- | --- |
| [LinkElement](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Methods

| Method | Description |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Adjust position. |
| [getHyperlink](#getHyperlink--) | Gets or Sets Hyperlink for Link Element. |
| [getStructureTextState](#getStructureTextState--) | Gets {@code /Aspose.Pdf.LogicalStructure.StructureTextState} object for current element. Value: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} object for current element. |
| [preSave](#preSave--) |  |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Gets or Sets Hyperlink for Link Element. |
| [setText](#setText-java.lang.String-) | Appends text content to current text element. |

### LinkElement {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Adjust position.

### getHyperlink {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```

Gets or Sets Hyperlink for Link Element.

**Returns:**
Hyperlink instance

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Gets {@code /Aspose.Pdf.LogicalStructure.StructureTextState} object for current element. Value: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} object for current element.

**Returns:**
Value: StructureTextState object for text structure element.

### preSave {#preSave--}
```
public void preSave()
```



### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Gets or Sets Hyperlink for Link Element.

### setText {#setText-java.lang.String-}
Appends text content to current text element.
