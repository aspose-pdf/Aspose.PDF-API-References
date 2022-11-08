---
title: StructureAttributeCollection
second_title: Aspose.PDF for Java API Reference
description: Represents collection of attributes of structure elements.
type: docs
weight: 15
url: /java/com.aspose.pdf.tagged.logicalstructure/structureattributecollection/
---
**Inheritance:**
java.lang.Object
```
public class StructureAttributeCollection
```

Represents collection of attributes of structure elements.
## Constructors

| Constructor | Description |
| --- | --- |
| [StructureAttributeCollection(IPdfPrimitive entityA, StructureElement structureElement)](#StructureAttributeCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) |  |
| [StructureAttributeCollection(StructureElement structureElement)](#StructureAttributeCollection-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) |  |
## Methods

| Method | Description |
| --- | --- |
| [createAttributes(AttributeOwnerStandard ownerStandard)](#createAttributes-com.aspose.pdf.tagged.logicalstructure.AttributeOwnerStandard-) | Create and return [StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) of structure element by standard attribute owner. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributes(AttributeOwnerStandard ownerStandard)](#getAttributes-com.aspose.pdf.tagged.logicalstructure.AttributeOwnerStandard-) | Return [StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) of structure element by standard attribute owner. |
| [getClass()](#getClass--) |  |
| [getEngineAttributeCollection()](#getEngineAttributeCollection--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructureAttributeCollection(IPdfPrimitive entityA, StructureElement structureElement) {#StructureAttributeCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
```
public StructureAttributeCollection(IPdfPrimitive entityA, StructureElement structureElement)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entityA | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |
| structureElement | [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) |  |

### StructureAttributeCollection(StructureElement structureElement) {#StructureAttributeCollection-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
```
public StructureAttributeCollection(StructureElement structureElement)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structureElement | [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) |  |

### createAttributes(AttributeOwnerStandard ownerStandard) {#createAttributes-com.aspose.pdf.tagged.logicalstructure.AttributeOwnerStandard-}
```
public final StructureAttributes createAttributes(AttributeOwnerStandard ownerStandard)
```


Create and return [StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) of structure element by standard attribute owner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerStandard | [AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) | Standard attribute owner. |

**Returns:**
[StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) - [StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) of structure element. Structure Attributes will be created if it needed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAttributes(AttributeOwnerStandard ownerStandard) {#getAttributes-com.aspose.pdf.tagged.logicalstructure.AttributeOwnerStandard-}
```
public final StructureAttributes getAttributes(AttributeOwnerStandard ownerStandard)
```


Return [StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) of structure element by standard attribute owner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerStandard | [AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) | Standard attribute owner. |

**Returns:**
[StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) - [StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) of structure element. Return null if not found.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEngineAttributeCollection() {#getEngineAttributeCollection--}
```
public final IPdfPrimitive getEngineAttributeCollection()
```




**Returns:**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

