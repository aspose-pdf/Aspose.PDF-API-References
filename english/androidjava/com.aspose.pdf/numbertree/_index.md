---
title: NumberTree
second_title: Aspose.PDF for Java API Reference
description: Class represeting Number tree structure of PDF file.  7.9.7Number Trees
type: docs
weight: 184
url: /java/com.aspose.pdf/numbertree/
---
**Inheritance:**
java.lang.Object
```
public class NumberTree
```

Class represeting Number tree structure of PDF file. 7.9.7Number Trees
## Constructors

| Constructor | Description |
| --- | --- |
| [NumberTree(IPdfDictionary root)](#NumberTree-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
## Methods

| Method | Description |
| --- | --- |
| [update(int key, IPdfDictionary item)](#update-int-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [remove(int key)](#remove-int-) | Remove key from number tree. |
| [get(int key)](#get-int-) | Gets item by key. |
| [getKeys()](#getKeys--) | Gets all keys in the tree. |
### NumberTree(IPdfDictionary root) {#NumberTree-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public NumberTree(IPdfDictionary root)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| root | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### update(int key, IPdfDictionary item) {#update-int-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void update(int key, IPdfDictionary item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int |  |
| item | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### remove(int key) {#remove-int-}
```
public boolean remove(int key)
```


Remove key from number tree.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int |  |

**Returns:**
boolean - 
### get(int key) {#get-int-}
```
public IPdfPrimitive get(int key)
```


Gets item by key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int |  |

**Returns:**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) - 
### getKeys() {#getKeys--}
```
public System.Collections.IList getKeys()
```


Gets all keys in the tree.

**Returns:**
com.aspose.ms.System.Collections.IList - 
