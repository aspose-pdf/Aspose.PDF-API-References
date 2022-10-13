---
title: Copier
second_title: Aspose.PDF for Java API Reference
description: Class for coping object
type: docs
weight: 69
url: /java/com.aspose.pdf/copier/
---
**Inheritance:**
java.lang.Object
```
public class Copier
```

Class for coping object
## Constructors

| Constructor | Description |
| --- | --- |
| [Copier(ITrailerable trailerable)](#Copier-com.aspose.pdf.engine.data.ITrailerable-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) |  |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) |  |
| [getReuseStreams()](#getReuseStreams--) |  |
| [setReuseStreams(boolean value)](#setReuseStreams-boolean-) |  |
| [getUseStubs()](#getUseStubs--) |  |
| [setUseStubs(boolean value)](#setUseStubs-boolean-) |  |
| [getRestrictedKeys()](#getRestrictedKeys--) |  |
| [setRestrictedKeys(String[] value)](#setRestrictedKeys-java.lang.String---) |  |
| [duplicate(IPdfPrimitive src)](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [duplicate(IPdfPrimitive src, boolean IsResourceObject)](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | Creates copy of object with all dependent object. |
### Copier(ITrailerable trailerable) {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
```
public Copier(ITrailerable trailerable)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) |  |

### getIgnoreCorruptedObjects() {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```




**Returns:**
boolean
### setIgnoreCorruptedObjects(boolean value) {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getReuseStreams() {#getReuseStreams--}
```
public boolean getReuseStreams()
```




**Returns:**
boolean
### setReuseStreams(boolean value) {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseStubs() {#getUseStubs--}
```
public boolean getUseStubs()
```




**Returns:**
boolean
### setUseStubs(boolean value) {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRestrictedKeys() {#getRestrictedKeys--}
```
public String[] getRestrictedKeys()
```




**Returns:**
java.lang.String[]
### setRestrictedKeys(String[] value) {#setRestrictedKeys-java.lang.String---}
```
public void setRestrictedKeys(String[] value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### duplicate(IPdfPrimitive src) {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public IPdfPrimitive duplicate(IPdfPrimitive src)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

**Returns:**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive)
### duplicate(IPdfPrimitive src, boolean IsResourceObject) {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
```
public IPdfPrimitive duplicate(IPdfPrimitive src, boolean IsResourceObject)
```


Creates copy of object with all dependent object. The object may be from part of other document (e.g. coping pages between documents, etc.)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |
| IsResourceObject | boolean |  |

**Returns:**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) - 
