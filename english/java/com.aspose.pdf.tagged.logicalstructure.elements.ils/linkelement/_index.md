---
title: LinkElement
second_title: Aspose.PDF for Java API Reference
description: Represents Link structure element in logical structure.
type: docs
weight: 16
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/ilselement), [com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/annotationelement)

**All Implemented Interfaces:**
[com.aspose.pdf.tagged.logicalstructure.elements.ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement)
```
public final class LinkElement extends AnnotationElement implements ITextElement
```

Represents Link structure element in logical structure.
## Constructors

| Constructor | Description |
| --- | --- |
| [LinkElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getHyperlink()](#getHyperlink--) | Gets or Sets Hyperlink for Link Element. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Gets or Sets Hyperlink for Link Element. |
| [getStructureTextState()](#getStructureTextState--) | Gets  /Aspose.Pdf.LogicalStructure.StructureTextState  object for current element. |
| [setText(String text)](#setText-java.lang.String-) | Appends text content to current text element. |
### LinkElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public LinkElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) |  |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

### getHyperlink() {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```


Gets or Sets Hyperlink for Link Element.

**Returns:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - Hyperlink instance
### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public final void setHyperlink(Hyperlink value)
```


Gets or Sets Hyperlink for Link Element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | Hyperlink instance |

### getStructureTextState() {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```


Gets  /Aspose.Pdf.LogicalStructure.StructureTextState  object for current element.

Value:  /Aspose.Pdf.LogicalStructure.StructureTextState  object for current element.

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
| text | java.lang.String | Text content. |

