---
title: StructureAttributes
second_title: Aspose.PDF for Java API Reference
description: Represents attributes of structure element for standard attribute owners.
type: docs
weight: 17
url: /java/com.aspose.pdf.tagged.logicalstructure/structureattributes/
---
**Inheritance:**
java.lang.Object
```
public class StructureAttributes
```

Represents attributes of structure element for standard attribute owners.
## Methods

| Method | Description |
| --- | --- |
| [getEngineAttributes()](#getEngineAttributes--) |  |
| [getOwner()](#getOwner--) | Gets standard attribute owner. |
| [getAttribute(AttributeKey key)](#getAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Gets StructureAttribute by AttributeKey. |
| [hasAttribute(AttributeKey key)](#hasAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) |  |
| [setAttribute(StructureAttribute attribute)](#setAttribute-com.aspose.pdf.tagged.logicalstructure.elements.StructureAttribute-) | Sets StructureAttribute into StructureAttributes. |
### getEngineAttributes() {#getEngineAttributes--}
```
public final IPdfDictionary getEngineAttributes()
```




**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary)
### getOwner() {#getOwner--}
```
public final AttributeOwnerStandard getOwner()
```


Gets standard attribute owner.

Value: Standard attribute owner.

**Returns:**
[AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) - AttributeOwnerStandard instance
### getAttribute(AttributeKey key) {#getAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
```
public final StructureAttribute getAttribute(AttributeKey key)
```


Gets StructureAttribute by AttributeKey.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) | AttributeKey. |

**Returns:**
[StructureAttribute](../../com.aspose.pdf.tagged.logicalstructure.elements/structureattribute) - StructureAttribute instance
### hasAttribute(AttributeKey key) {#hasAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
```
public final boolean hasAttribute(AttributeKey key)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) |  |

**Returns:**
boolean
### setAttribute(StructureAttribute attribute) {#setAttribute-com.aspose.pdf.tagged.logicalstructure.elements.StructureAttribute-}
```
public final void setAttribute(StructureAttribute attribute)
```


Sets StructureAttribute into StructureAttributes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attribute | [StructureAttribute](../../com.aspose.pdf.tagged.logicalstructure.elements/structureattribute) | StructureAttribute. |

