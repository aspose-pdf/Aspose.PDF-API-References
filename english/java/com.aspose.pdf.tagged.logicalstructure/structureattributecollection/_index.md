---
title: StructureAttributeCollection
second_title: Aspose.PDF for Java API Reference
description: Represents collection of attributes of structure elements.
type: docs
weight: 16
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
| [getEngineAttributeCollection()](#getEngineAttributeCollection--) |  |
| [getAttributes(AttributeOwnerStandard ownerStandard)](#getAttributes-com.aspose.pdf.tagged.logicalstructure.AttributeOwnerStandard-) | Return [StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) of structure element by standard attribute owner. |
| [createAttributes(AttributeOwnerStandard ownerStandard)](#createAttributes-com.aspose.pdf.tagged.logicalstructure.AttributeOwnerStandard-) | Create and return [StructureAttributes](../../com.aspose.pdf.tagged.logicalstructure/structureattributes) of structure element by standard attribute owner. |
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

### getEngineAttributeCollection() {#getEngineAttributeCollection--}
```
public final IPdfPrimitive getEngineAttributeCollection()
```




**Returns:**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive)
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
