---
title: Document.OptimizationOptions
second_title: Aspose.PDF for Java API Reference
description: Class which describes document optimization algorithm.
type: docs
weight: 10
url: /java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public static class Document.OptimizationOptions
```

Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method.
## Constructors

| Constructor | Description |
| --- | --- |
| [OptimizationOptions()](#OptimizationOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLinkDuplcateStreams()](#getLinkDuplcateStreams--) | If this flag is set to true, Resource streams will be analyzed. |
| [setLinkDuplcateStreams(boolean value)](#setLinkDuplcateStreams-boolean-) | If this flag is set to true, Resource streams will be analyzed. |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | If this flag set to true, every resource is checked on it's usage. |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | If this flag set to true, every resource is checked on it's usage. |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [All()](#All--) | Creates optimization strategy will all options activated. |
### OptimizationOptions() {#OptimizationOptions--}
```
public OptimizationOptions()
```


### getLinkDuplcateStreams() {#getLinkDuplcateStreams--}
```
public boolean getLinkDuplcateStreams()
```


If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then thes streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenedted multiple times).

**Returns:**
boolean - 
### setLinkDuplcateStreams(boolean value) {#setLinkDuplcateStreams-boolean-}
```
public void setLinkDuplcateStreams(boolean value)
```


If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then thes streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenedted multiple times).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public boolean getRemoveUnusedStreams()
```


If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document.

**Returns:**
boolean - boolean value
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean value)
```


If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public boolean getRemoveUnusedObjects()
```


If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document.

**Returns:**
boolean - boolean value
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean value)
```


If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### All() {#All--}
```
public static Document.OptimizationOptions All()
```


Creates optimization strategy will all options activated.

**Returns:**
[OptimizationOptions](../../com.aspose.pdf/optimizationoptions) - 
