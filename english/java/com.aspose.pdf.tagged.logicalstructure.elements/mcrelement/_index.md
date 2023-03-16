---
title: MCRElement
second_title: Aspose.PDF for Java API Reference
description: Represents marked-content reference object in logical structure.
type: docs
weight: 15
url: /java/com.aspose.pdf.tagged.logicalstructure.elements/mcrelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
```
public final class MCRElement extends Element
```

Represents marked-content reference object in logical structure.
## Constructors

| Constructor | Description |
| --- | --- |
## Methods

| Method | Description |
| --- | --- |
| [setHyperlink(Hyperlink hyperlink)](#setHyperlink-com.aspose.pdf.Hyperlink-) |  |
| [isCreatedElement()](#isCreatedElement--) |  |
| [getPage()](#getPage--) | Get Page instance |
| [setPage(Page value)](#setPage-com.aspose.pdf.Page-) | Set Page instance |
| [setNewMCID(int value)](#setNewMCID-int-) | Get MCID value |
| [setBdcOperator(BDC value)](#setBdcOperator-com.aspose.pdf.operators.BDC-) | Set BDC Operator |
| [getImageSrc()](#getImageSrc--) | Gets image source for marked-content reference element. |
| [setImageSrc(String value)](#setImageSrc-java.lang.String-) | Gets image source for marked-content reference element. |
| [getImageResolution()](#getImageResolution--) | For internal usage only |
| [setImageResolution(Double[] value)](#setImageResolution-java.lang.Double---) | For internal usage only |
| [getImageWidth()](#getImageWidth--) | For internal usage only |
| [setImageWidth(Double[] value)](#setImageWidth-java.lang.Double---) | For internal usage only |
| [getImageHeight()](#getImageHeight--) | For internal usage only |
| [setImageHeight(Double[] value)](#setImageHeight-java.lang.Double---) | For internal usage only |
| [getContent()](#getContent--) | Gets text content for marked-content reference element. |
| [setContent(String value)](#setContent-java.lang.String-) | Gets text content for marked-content reference element. |
| [getMCID()](#getMCID--) | Gets MCID of marked-content reference object. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### setHyperlink(Hyperlink hyperlink) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public final void setHyperlink(Hyperlink hyperlink)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hyperlink | [Hyperlink](../../com.aspose.pdf/hyperlink) |  |

### isCreatedElement() {#isCreatedElement--}
```
public final boolean isCreatedElement()
```




**Returns:**
boolean
### getPage() {#getPage--}
```
public final Page getPage()
```


Get Page instance

**Returns:**
[Page](../../com.aspose.pdf/page) - Page instance
### setPage(Page value) {#setPage-com.aspose.pdf.Page-}
```
public final void setPage(Page value)
```


Set Page instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | Page instance |

### setNewMCID(int value) {#setNewMCID-int-}
```
public final void setNewMCID(int value)
```


Get MCID value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | MCID value |

### setBdcOperator(BDC value) {#setBdcOperator-com.aspose.pdf.operators.BDC-}
```
public final void setBdcOperator(BDC value)
```


Set BDC Operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BDC](../../com.aspose.pdf.operators/bdc) | BDC Operator |

### getImageSrc() {#getImageSrc--}
```
public final String getImageSrc()
```


Gets image source for marked-content reference element.

For just created [IllustrationElement](../../com.aspose.pdf.tagged.logicalstructure.elements/illustrationelement). Is null in other cases.

**Returns:**
java.lang.String - Image source for marked-content reference element.
### setImageSrc(String value) {#setImageSrc-java.lang.String-}
```
public final void setImageSrc(String value)
```


Gets image source for marked-content reference element.

For just created [IllustrationElement](../../com.aspose.pdf.tagged.logicalstructure.elements/illustrationelement). Is null in other cases.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Image source for marked-content reference element. |

### getImageResolution() {#getImageResolution--}
```
public final Double[] getImageResolution()
```


For internal usage only

**Returns:**
java.lang.Double[] - For internal usage only
### setImageResolution(Double[] value) {#setImageResolution-java.lang.Double---}
```
public final void setImageResolution(Double[] value)
```


For internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double[] | For internal usage only |

### getImageWidth() {#getImageWidth--}
```
public final Double[] getImageWidth()
```


For internal usage only

**Returns:**
java.lang.Double[] - For internal usage only
### setImageWidth(Double[] value) {#setImageWidth-java.lang.Double---}
```
public final void setImageWidth(Double[] value)
```


For internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double[] | For internal usage only |

### getImageHeight() {#getImageHeight--}
```
public final Double[] getImageHeight()
```


For internal usage only

**Returns:**
java.lang.Double[] - For internal usage only
### setImageHeight(Double[] value) {#setImageHeight-java.lang.Double---}
```
public final void setImageHeight(Double[] value)
```


For internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double[] | For internal usage only |

### getContent() {#getContent--}
```
public final String getContent()
```


Gets text content for marked-content reference element.

For just created object wich implement [ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement). Is null in other cases.

**Returns:**
java.lang.String - Text content for marked-content reference element.
### setContent(String value) {#setContent-java.lang.String-}
```
public final void setContent(String value)
```


Gets text content for marked-content reference element.

For just created object wich implement [ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement). Is null in other cases.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Text content for marked-content reference element. |

### getMCID() {#getMCID--}
```
public final int getMCID()
```


Gets MCID of marked-content reference object.

**Returns:**
int - MCID of marked-content reference object.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - String that represents the current object.
