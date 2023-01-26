---
title: Group
second_title: Aspose.PDF for Java API Reference
description: A group attributes class specifying the attributes of the pageu2019s page group for use in the transparent imaging model.
type: docs
weight: 151
url: /java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object
```
public final class Group
```

A group attributes class specifying the attributes of the page\\u2019s page group for use in the transparent imaging model.
## Constructors

| Constructor | Description |
| --- | --- |
| [Group(Page page)](#Group-com.aspose.pdf.Page-) | The constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getColorSpace()](#getColorSpace--) | Gets ColorSpace |
| [setColorSpace(int value)](#setColorSpace-int-) | The group color space. |
| [isTransparency()](#isTransparency--) | for Internal usage only |
| [isKnockout()](#isKnockout--) | for Internal usage only |
| [setKnockout(int value)](#setKnockout-int-) | If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group\\u2019s initial backdrop and overwrite (\\u201cknock out\\u201d) any earlier overlapping objects. |
### Group(Page page) {#Group-com.aspose.pdf.Page-}
```
public Group(Page page)
```


The constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf page object. |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Gets ColorSpace

**Returns:**
int - ColorSpace value.
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


The group color space.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ColorSpace value. |

### isTransparency() {#isTransparency--}
```
public boolean isTransparency()
```


for Internal usage only

returns The group transparency flag.

**Returns:**
boolean - boolean value
### isKnockout() {#isKnockout--}
```
public int isKnockout()
```


for Internal usage only

If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group\\u2019s initial backdrop and overwrite (\\u201cknock out\\u201d) any earlier overlapping objects.

**Returns:**
int - ExtendedBoolean element
### setKnockout(int value) {#setKnockout-int-}
```
public void setKnockout(int value)
```


If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group\\u2019s initial backdrop and overwrite (\\u201cknock out\\u201d) any earlier overlapping objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ExtendedBoolean element |

