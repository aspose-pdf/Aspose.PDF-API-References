---
title: Group
second_title: Aspose.PDF for Java API Reference
description: A group attributes class specifying the attributes of the pageu2019s page group for use in the transparent imaging model.
type: docs
weight: 126
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
| [getColorSpace()](#getColorSpace--) | The group color space. |
| [setColorSpace(int value)](#setColorSpace-int-) |  |
| [isKnockout()](#isKnockout--) | If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group\\u2019s initial backdrop and overwrite (\\u201cknock out\\u201d) any earlier overlapping objects. |
| [isKnockout(int value)](#isKnockout-int-) |  |
### Group(Page page) {#Group-com.aspose.pdf.Page-}
```
public Group(Page page)
```


The constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page. |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


The group color space.

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isKnockout() {#isKnockout--}
```
public int isKnockout()
```


If this flag is false, later objects within the group are composited with earlier ones with which they overlap; if true, they are composited with the group\\u2019s initial backdrop and overwrite (\\u201cknock out\\u201d) any earlier overlapping objects.

**Returns:**
int
### isKnockout(int value) {#isKnockout-int-}
```
public void isKnockout(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

