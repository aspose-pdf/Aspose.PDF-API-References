---
title: Element
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for element in logical structure.
type: docs
weight: 10
url: /java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

Represents a base class for element in logical structure.

## Methods

| Method | Description |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Append {@code /Aspose.Pdf.LogicalStructure.Element} to collection of children. |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Append {@code /Aspose.Pdf.LogicalStructure.Element} to collection of children. |
| [clearChilds](#clearChilds--) | Clear all childs. |
| [findElements](#findElements-java.lang.Class-) | Find Elements of a given type |
| [findElements](#findElements-java.lang.Class-boolean-) | Find Elements of a given type |
| [getChildElements](#getChildElements--) | Gets children collection of {@code Element} objects. |
| [getElementEngine](#getElementEngine--) | Get parent element. |
| [getParentElement](#getParentElement--) | Gets parent collection of {@code Element} objects. |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | Internal method |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Insert {@code /Aspose.Pdf.LogicalStructure.Element} to collection of children at specified index. |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | Insert {@code /Aspose.Pdf.LogicalStructure.Element} to collection of children at specified index. |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | Remove child at. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | Bind a structure element to the Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Bind a structure element to the Artifact. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Bind a structure element to the content stream BDC operator. |
| [tag](#tag-com.aspose.pdf.XForm-) | Bind a structure element to the content stream XForm. |
| [tag](#tag-com.aspose.pdf.XImage-) | Bind a structure element to the XImage. |
| [toString](#toString--) | Returns a string that represents the current object. |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Append {@code /Aspose.Pdf.LogicalStructure.Element} to collection of children.

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Append {@code /Aspose.Pdf.LogicalStructure.Element} to collection of children.

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

Clear all childs.

### findElements {#findElements-java.lang.Class-}
Find Elements of a given type

### findElements {#findElements-java.lang.Class-boolean-}
Find Elements of a given type

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

Gets children collection of {@code Element} objects.

**Returns:**
Value: Children collection of {@code Element} objects.

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

Get parent element.

**Returns:**
Value: Parent element.

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

Gets parent collection of {@code Element} objects.

**Returns:**
Value: Parent collection of {@code Element} objects.

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

Internal method

**Returns:**
Internal element

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Insert {@code /Aspose.Pdf.LogicalStructure.Element} to collection of children at specified index.

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
Insert {@code /Aspose.Pdf.LogicalStructure.Element} to collection of children at specified index.

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

Remove child at.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Child element index. |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### tag {#tag-com.aspose.pdf.Annotation-}
Bind a structure element to the Annotation.

### tag {#tag-com.aspose.pdf.Artifact-}
Bind a structure element to the Artifact.

### tag {#tag-com.aspose.pdf.operators.BDC-}
Bind a structure element to the content stream BDC operator.

### tag {#tag-com.aspose.pdf.XForm-}
Bind a structure element to the content stream XForm.

### tag {#tag-com.aspose.pdf.XImage-}
Bind a structure element to the XImage.

### toString {#toString--}
```
public String toString()
```

Returns a string that represents the current object.

**Returns:**
String that represents the current object.
