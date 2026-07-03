---
title: StructureElement
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for structure elements in logical structure.
type: docs
weight: 110
url: /java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

Represents a base class for structure elements in logical structure.

## Methods

| Method | Description |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Change parent element for current structure element |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | Change parent element for current structure element |
| [clearId](#clearId--) | Clear ID for structure element. |
| [generateId](#generateId--) | Generate ID for structure element. |
| [getActualText](#getActualText--) | Gets or sets the actual text for structure element. |
| [getAlternativeText](#getAlternativeText--) | Gets or sets the alternative text for structure element. |
| [getAttributes](#getAttributes--) | Gets {@code StructureAttributeCollection} object. |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | Gets {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} object. Value: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} object. |
| [getExpansionText](#getExpansionText--) | Gets or sets the expansion text for structure element. |
| [getID](#getID--) | Gets the ID for structure element. Value: ID of the structure element. |
| [getLanguage](#getLanguage--) | Gets or sets the language for structure element. |
| [getPage](#getPage--) | Gets the page on which some or all child elements will be rendered. |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | Gets type of structure element. |
| [getTitle](#getTitle--) | Gets or sets the title for structure element. |
| [remove](#remove--) | Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects, and the corresponding object from the document. Inserts child objects of the removed object into its former parent child objects collection starting at the index of the removed object. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | Removes an element from the structure, a reference to it from the parent object, references to it from child objects, and the corresponding object from the document. Inserts child objects of the removed object into its former parent child objects collection starting at the index of the removed object. |
| [setActualText](#setActualText-java.lang.String-) | Gets or sets the actual text for structure element. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Gets or sets the alternative text for structure element. |
| [setExpansionText](#setExpansionText-java.lang.String-) | Gets or sets the expansion text for structure element. |
| [setId](#setId-java.lang.String-) | Sets ID for structure element. |
| [setLanguage](#setLanguage-java.lang.String-) | Gets or sets the language for structure element. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | set Parent Element |
| [setTag](#setTag-java.lang.String-) | Sets custom tag for structure element. |
| [setTitle](#setTitle-java.lang.String-) | Gets or sets the title for structure element. |
| [tag](#tag-com.aspose.pdf.Annotation-) | Bind a structure element to the Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Bind a structure element to the Artifact. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Bind a structure element to the content stream BDC operator. |
| [tag](#tag-com.aspose.pdf.XForm-) | Bind a structure element to the content stream XForm. |
| [tag](#tag-com.aspose.pdf.XImage-) | Bind a structure element to the XImage. |
| [toString](#toString--) | Returns a string that represents the current object. |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Change parent element for current structure element

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
Change parent element for current structure element

### clearId {#clearId--}
```
public final void clearId()
```

Clear ID for structure element.

### generateId {#generateId--}
```
public final void generateId()
```

Generate ID for structure element.

### getActualText {#getActualText--}
```
public final String getActualText()
```

Gets or sets the actual text for structure element.

**Returns:**
Value: Actual text of the structure element.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Gets or sets the alternative text for structure element.

**Returns:**
Value: Alternative text of the structure element.

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

Gets {@code StructureAttributeCollection} object.

**Returns:**
{@code StructureAttributeCollection} object.

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

Gets {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} object. Value: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} object.

**Returns:**
AttributeOwnerStandard instance

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

Gets or sets the expansion text for structure element.

**Returns:**
Value: Expansion text of the structure element.

### getID {#getID--}
```
public final String getID()
```

Gets the ID for structure element. Value: ID of the structure element.

**Returns:**
String value

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

Gets or sets the language for structure element.

**Returns:**
Value: Language of the structure element.

### getPage {#getPage--}
```
public final Page getPage()
```

Gets the page on which some or all child elements will be rendered.

**Returns:**
Page instance

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

Gets type of structure element.

**Returns:**
Value: {@code StructureTypeStandard} object of structure element.

### getTitle {#getTitle--}
```
public final String getTitle()
```

Gets or sets the title for structure element.

**Returns:**
Value: Title of the structure element.

### remove {#remove--}
```
public final void remove()
```

Removes: an element from the structure, a reference to it from the parent object, references to it from child objects, the corresponding object from the document.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

Removes an element from the structure, a reference to it from the parent object, references to it from child objects, and the corresponding object from the document. Inserts child objects of the removed object into its former parent child objects collection starting at the index of the removed object.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

Removes an element from the structure, a reference to it from the parent object, references to it from child objects, and the corresponding object from the document. Inserts child objects of the removed object into its former parent child objects collection starting at the index of the removed object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | Check if child objects of removed object can be inserted into its parent child objects collection. |

### setActualText {#setActualText-java.lang.String-}
Gets or sets the actual text for structure element.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Gets or sets the alternative text for structure element.

### setExpansionText {#setExpansionText-java.lang.String-}
Gets or sets the expansion text for structure element.

### setId {#setId-java.lang.String-}
Sets ID for structure element.

### setLanguage {#setLanguage-java.lang.String-}
Gets or sets the language for structure element.

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
set Parent Element

### setTag {#setTag-java.lang.String-}
Sets custom tag for structure element.

### setTitle {#setTitle-java.lang.String-}
Gets or sets the title for structure element.

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
