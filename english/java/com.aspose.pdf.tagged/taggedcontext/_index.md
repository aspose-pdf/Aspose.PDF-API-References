---
title: TaggedContext
second_title: Aspose.PDF for Java API Reference
description: For internal usage only
type: docs
weight: 10
url: /java/com.aspose.pdf.tagged/taggedcontext/
---
**Inheritance:**
java.lang.Object
```
public class TaggedContext
```

For internal usage only
## Methods

| Method | Description |
| --- | --- |
| [getNextMCID()](#getNextMCID--) |  |
| [updateLastMCID(int mcid)](#updateLastMCID-int-) |  |
| [getTrailer()](#getTrailer--) |  |
| [getDocument()](#getDocument--) |  |
| [getCurrentPage()](#getCurrentPage--) |  |
| [getStructTreeRootElement()](#getStructTreeRootElement--) |  |
| [pageRegisterMCRElement(Page page, MCRElement mcrElement)](#pageRegisterMCRElement-com.aspose.pdf.Page-com.aspose.pdf.tagged.logicalstructure.elements.MCRElement-) |  |
| [pageRegisterTableElement(Page page, TableElement tableStructureElement)](#pageRegisterTableElement-com.aspose.pdf.Page-com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement-) |  |
### getNextMCID() {#getNextMCID--}
```
public final int getNextMCID()
```




**Returns:**
int
### updateLastMCID(int mcid) {#updateLastMCID-int-}
```
public final void updateLastMCID(int mcid)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mcid | int |  |

### getTrailer() {#getTrailer--}
```
public final ITrailerable getTrailer()
```




**Returns:**
[ITrailerable](../../com.aspose.pdf.engine.data/itrailerable)
### getDocument() {#getDocument--}
```
public final IDocument getDocument()
```




**Returns:**
[IDocument](../../com.aspose.pdf/idocument)
### getCurrentPage() {#getCurrentPage--}
```
public final Page getCurrentPage()
```




**Returns:**
[Page](../../com.aspose.pdf/page)
### getStructTreeRootElement() {#getStructTreeRootElement--}
```
public final StructTreeRootElement getStructTreeRootElement()
```




**Returns:**
[StructTreeRootElement](../../com.aspose.pdf.tagged.logicalstructure/structtreerootelement)
### pageRegisterMCRElement(Page page, MCRElement mcrElement) {#pageRegisterMCRElement-com.aspose.pdf.Page-com.aspose.pdf.tagged.logicalstructure.elements.MCRElement-}
```
public final void pageRegisterMCRElement(Page page, MCRElement mcrElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| mcrElement | [MCRElement](../../com.aspose.pdf.tagged.logicalstructure.elements/mcrelement) |  |

### pageRegisterTableElement(Page page, TableElement tableStructureElement) {#pageRegisterTableElement-com.aspose.pdf.Page-com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement-}
```
public final void pageRegisterTableElement(Page page, TableElement tableStructureElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| tableStructureElement | [TableElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement) |  |

