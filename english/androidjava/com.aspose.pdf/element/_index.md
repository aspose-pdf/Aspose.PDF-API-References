---
title: Element
second_title: Aspose.PDF for Java API Reference
description: Class representing base element of logical structure.
type: docs
weight: 82
url: /java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object
```
public abstract class Element
```

Class representing base element of logical structure.
## Methods

| Method | Description |
| --- | --- |
| [getChildren()](#getChildren--) | Gets child elements collection. |
| [getLang()](#getLang--) | (Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content. |
| [setLang(String value)](#setLang-java.lang.String-) |  |
| [getActualText()](#getActualText--) | (Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. |
| [setActualText(String value)](#setActualText-java.lang.String-) |  |
| [getAlt()](#getAlt--) | (Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes. |
| [setAlt(String value)](#setAlt-java.lang.String-) |  |
| [getE()](#getE--) | (Optional; PDF 1.5) The expanded form of an abbreviation. |
| [setE(String value)](#setE-java.lang.String-) |  |
### getChildren() {#getChildren--}
```
public System.Collections.ArrayList getChildren()
```


Gets child elements collection.

**Returns:**
com.aspose.ms.System.Collections.ArrayList
### getLang() {#getLang--}
```
public String getLang()
```


(Optional; PDF 1.4) A language specifying the natural language for all text in the structure element except where overridden by language specifications for nested structure elements or marked content.

**Returns:**
java.lang.String
### setLang(String value) {#setLang-java.lang.String-}
```
public void setLang(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getActualText() {#getActualText--}
```
public String getActualText()
```


(Optional; PDF 1.4) Text that is an exact replacement for the structure element and its children. This replacement text (which should apply to as small a piece of content as possible) is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes.

**Returns:**
java.lang.String
### setActualText(String value) {#setActualText-java.lang.String-}
```
public void setActualText(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlt() {#getAlt--}
```
public String getAlt()
```


(Optional) An alternate description of the structure element and its children in human-readableform, which is useful when extracting the document\\u2019s contents in support of accessibility to users with disabilities or for other purposes.

**Returns:**
java.lang.String
### setAlt(String value) {#setAlt-java.lang.String-}
```
public void setAlt(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getE() {#getE--}
```
public String getE()
```


(Optional; PDF 1.5) The expanded form of an abbreviation.

**Returns:**
java.lang.String
### setE(String value) {#setE-java.lang.String-}
```
public void setE(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

