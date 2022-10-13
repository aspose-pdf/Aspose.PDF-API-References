---
title: XfaMerge
second_title: Aspose.PDF for Java API Reference
description: Internal class for XFA merging operations
type: docs
weight: 328
url: /java/com.aspose.pdf/xfamerge/
---
**Inheritance:**
java.lang.Object
```
public class XfaMerge
```

Internal class for XFA merging operations
## Constructors

| Constructor | Description |
| --- | --- |
| [XfaMerge(IDocument dest)](#XfaMerge-com.aspose.pdf.IDocument-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getRootCreated()](#getRootCreated--) |  |
| [append(IDocument src, HashDictionary<String,String> RenameMap)](#append-com.aspose.pdf.IDocument-com.aspose.pdf.engine.collections.HashDictionary-java.lang.String-java.lang.String--) | Appends XFA form of soruce document to destination docyument |
| [resynAcroForm()](#resynAcroForm--) |  |
### XfaMerge(IDocument dest) {#XfaMerge-com.aspose.pdf.IDocument-}
```
public XfaMerge(IDocument dest)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dest | [IDocument](../../com.aspose.pdf/idocument) |  |

### getRootCreated() {#getRootCreated--}
```
public boolean getRootCreated()
```




**Returns:**
boolean
### append(IDocument src, HashDictionary<String,String> RenameMap) {#append-com.aspose.pdf.IDocument-com.aspose.pdf.engine.collections.HashDictionary-java.lang.String-java.lang.String--}
```
public void append(IDocument src, HashDictionary<String,String> RenameMap)
```


Appends XFA form of soruce document to destination docyument

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [IDocument](../../com.aspose.pdf/idocument) |  |
| RenameMap | com.aspose.pdf.engine.collections.HashDictionary<java.lang.String,java.lang.String> | Map of field renamings |

### resynAcroForm() {#resynAcroForm--}
```
public void resynAcroForm()
```




