---
title: StructureElement
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for structure elements in logical structure.
type: docs
weight: 18
url: /java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
```
public abstract class StructureElement extends Element
```

Represents a base class for structure elements in logical structure.
## Methods

| Method | Description |
| --- | --- |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | Gets  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object. |
| [getAttributes()](#getAttributes--) | Gets  StructureAttributeCollection  object. |
| [getStructureType()](#getStructureType--) | Gets type of structure element. |
| [getS()](#getS--) |  |
| [getID()](#getID--) | Gets the ID for structure element. |
| [getTitle()](#getTitle--) | Gets or sets the title for structure element. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gets or sets the title for structure element. |
| [getLanguage()](#getLanguage--) | Gets or sets the language for structure element. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Gets or sets the language for structure element. |
| [getAlternativeText()](#getAlternativeText--) | Gets or sets the alternative text for structure element. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Gets or sets the alternative text for structure element. |
| [getExpansionText()](#getExpansionText--) | Gets or sets the expansion text for structure element. |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | Gets or sets the expansion text for structure element. |
| [getActualText()](#getActualText--) | Gets or sets the actual text for structure element. |
| [setActualText(String value)](#setActualText-java.lang.String-) | Gets or sets the actual text for structure element. |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | set Parent Element |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Change parent element for current structure element |
| [generateId()](#generateId--) | Generate ID for structure element. |
| [setId(String id)](#setId-java.lang.String-) | Sets ID for structure element. |
| [clearId()](#clearId--) | Clear ID for structure element. |
| [setTag(String newTag)](#setTag-java.lang.String-) | Sets custom tag for structure element. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### getDefaultAttributeOwner() {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```


Gets  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object.

Value:  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object.

**Returns:**
[AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) - AttributeOwnerStandard instance
### getAttributes() {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```


Gets  StructureAttributeCollection  object.

**Returns:**
[StructureAttributeCollection](../../com.aspose.pdf.tagged.logicalstructure/structureattributecollection) -  StructureAttributeCollection  object.
### getStructureType() {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```


Gets type of structure element.

**Returns:**
[StructureTypeStandard](../../com.aspose.pdf.tagged.logicalstructure/structuretypestandard) - Value:  StructureTypeStandard  object of structure element.
### getS() {#getS--}
```
public final IPdfName getS()
```




**Returns:**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname)
### getID() {#getID--}
```
public final String getID()
```


Gets the ID for structure element.

Value: ID of the structure element.

**Returns:**
java.lang.String - String value
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets or sets the title for structure element.

**Returns:**
java.lang.String - Value: Title of the structure element.
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Gets or sets the title for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Title of the structure element. |

### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets or sets the language for structure element.

**Returns:**
java.lang.String - Value: Language of the structure element.
### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


Gets or sets the language for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Language of the structure element. |

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Gets or sets the alternative text for structure element.

**Returns:**
java.lang.String - Value: Alternative text of the structure element.
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Gets or sets the alternative text for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Alternative text of the structure element. |

### getExpansionText() {#getExpansionText--}
```
public final String getExpansionText()
```


Gets or sets the expansion text for structure element.

**Returns:**
java.lang.String - Value: Expansion text of the structure element.
### setExpansionText(String value) {#setExpansionText-java.lang.String-}
```
public final void setExpansionText(String value)
```


Gets or sets the expansion text for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Expansion text of the structure element. |

### getActualText() {#getActualText--}
```
public final String getActualText()
```


Gets or sets the actual text for structure element.

**Returns:**
java.lang.String - Value: Actual text of the structure element.
### setActualText(String value) {#setActualText-java.lang.String-}
```
public final void setActualText(String value)
```


Gets or sets the actual text for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Actual text of the structure element. |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


set Parent Element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | value |

### changeParentElement(StructureElement newParentElement) {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
```
public final void changeParentElement(StructureElement newParentElement)
```


Change parent element for current structure element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newParentElement | [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) | New parent structure element |

### generateId() {#generateId--}
```
public final void generateId()
```


Generate ID for structure element.

### setId(String id) {#setId-java.lang.String-}
```
public final void setId(String id)
```


Sets ID for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | ID value for structure element |

### clearId() {#clearId--}
```
public final void clearId()
```


Clear ID for structure element.

### setTag(String newTag) {#setTag-java.lang.String-}
```
public final void setTag(String newTag)
```


Sets custom tag for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newTag | java.lang.String | Tag name |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - String that represents the current object.
