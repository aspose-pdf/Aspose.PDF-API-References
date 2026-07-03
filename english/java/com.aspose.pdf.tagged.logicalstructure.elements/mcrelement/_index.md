---
title: MCRElement
second_title: Aspose.PDF for Java API Reference
description: Represents marked-content reference object in logical structure.
type: docs
weight: 80
url: /java/com.aspose.pdf.tagged.logicalstructure.elements/mcrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.MCRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.MCRElement

```
public final class MCRElement extends Element
```

Represents marked-content reference object in logical structure.

## Fields

| Field | Description |
| --- | --- |
| [Handler](#Handler) |  |

## Constructors

| Constructor | Description |
| --- | --- |
| [MCRElement](#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [getMCID](#getMCID--) | Gets MCID of marked-content reference object. |
| [getPage](#getPage--) | Get Page instance |
| [preSave](#preSave--) |  |
| [setNewMCID](#setNewMCID-int-) | Get MCID value |
| [setPage](#setPage-com.aspose.pdf.Page-) | Set Page instance |
| [tag](#tag-com.aspose.pdf.Annotation-) | Bind a structure element to the Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Bind a structure element to the Artifact. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Bind a structure element to the content stream BDC operator. |
| [tag](#tag-com.aspose.pdf.XForm-) | Bind a structure element to the content stream XForm. |
| [tag](#tag-com.aspose.pdf.XImage-) | Bind a structure element to the XImage. |
| [toString](#toString--) | Returns a string that represents the current object. |

### Handler {#Handler}
```
public com.aspose.pdf.tagged.helpers.logicalstructure.MCRElementHandler Handler
```



### MCRElement {#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
Constructor

### getMCID {#getMCID--}
```
public final int getMCID()
```

Gets MCID of marked-content reference object.

**Returns:**
MCID of marked-content reference object.

### getPage {#getPage--}
```
public final Page getPage()
```

Get Page instance

**Returns:**
Page instance

### preSave {#preSave--}
```
public void preSave()
```



### setNewMCID {#setNewMCID-int-}
```
public final void setNewMCID(int value)
```

Get MCID value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | MCID value |

### setPage {#setPage-com.aspose.pdf.Page-}
Set Page instance

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
